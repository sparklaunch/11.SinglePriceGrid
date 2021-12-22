<div id="plan">
    <h2>Monthly Subscription</h2>
    <div id="price">
        <p class="price">$29</p>
        <p class="per">per month</p>
    </div>
    <p>Full access for less than $1 a day</p>
    <button>Sign Up</button>
</div>

<style>
    #plan {
        display: flex;
        flex-direction: column;
        justify-content: center;
        width: 50%;
        background-color: rgb(38, 170, 168);
        padding: 40px;
    }
    #plan > h2 {
        color: white;
        margin-bottom: 20px;
    }
    #price {
        display: flex;
        align-items: center;
        margin-bottom: 5px;
    }
    #price > p.price {
        color: white;
        font-size: 36px;
        margin-right: 10px;
    }
    #price > p.per {
        color: white;
        opacity: 0.5;
    }
    #plan > p {
        color: white;
        opacity: 0.75;
        margin-bottom: 30px;
    }
    #plan > button {
        border: none;
        border-radius: 5px;
        background-color: rgb(183, 219, 44);
        color: white;
        width: 100%;
        padding: 15px 0;
        font-size: 20px;
        box-shadow: 10px 10px 10px rgba(0, 0, 0, 0.1);
        cursor: pointer;
        transition: filter 0.3s;
    }
    #plan > button:hover {
        filter: brightness(0.9);
    }
    #plan > button:active {
        filter: brightness(1.1);
    }
</style>
