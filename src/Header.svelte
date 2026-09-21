<script>
    import bitcoinPay from './assets/bitcoinpay.svg'
</script>

<header>
    <a href="/">
        <img src={bitcoinPay} class="base" width="170" height="179" alt="" />
    </a>
    <nav>
        <ul>
        </ul>
    </nav>
</header>

<style>
    header{
        display: flex;

        a {
            margin:  auto auto auto 3.5vw;
            display: flex;
            justify-content: center;
        }

        img {
            height: 6em;
            width: 6em;
            margin: auto;
        }

        nav {
            display: flex;
            justify-content: center;
            width: 100%;

            ul {
                display: flex;
                padding: 0;
                list-style: none;
                justify-content: center;
                align-items: center;
            }
        }
    }
</style>