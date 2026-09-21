<script>
    import payWidget from "./assets/pay_widget.svg"
</script>

<section>
    <div>
        <h1>
            Bitcoin Is Money.
            Accept Bitcoin Payments With 0% Fees On Your Own Terms.
        </h1>
        <h2>
            BitcoinPay Server is a Bitcoin only
            payment processor, it is Free and Open-Source, you can run it yourself.
            Run it, Become <b>Self Sovereign</b>.
        </h2>
    </div>
    <img src={payWidget} alt="Pay Widget" />
</section>

<style>
    section {
        display: flex;
        padding: 32px;
        margin: auto;
        max-width: 1024px;
        justify-content: center;
        align-items: center;
        div {
            margin-right: 128px;
            h1 {
                text-align: left;
                line-height: 1.5;
                font-family: sans-serif;
                font-size: 3em;
                font-weight: bold;
            }

            h2 {
                line-height: 1.5;
                text-align: left;
                font-size: 18px;
                font-family: sans-serif;
            }
        }

        img {
            max-width: 24em;
            max-height: 32em;

        }
    }
</style>