<img style="border-radius: 10px;" src="assets/images/metatrader_header.jpg" alt="Export MQL5 strategies from Forex Strategy Studio and run them in MetaTrader 5"/>

# Forex Strategy Studio - MQL5 Expert Advisors

A curated collection of **MetaTrader 5 (MT5) Expert Advisors** exported from **Forex Strategy Studio**.<br/><br/>
Build your MetaTrader 5 Expert Advisor in the no-code Forex Strategy Studio Strategy Builder, then export them with a click to MQL5 and run them in MetaTrader 5 for live trading or backtesting.

Forex Strategy Studio takes you from <strong>idea</strong> &rarr; <strong>strategy</strong> &rarr; <strong>backtest</strong> &rarr; <strong>execution</strong> without the usual friction.

➡️ Create and refine your strategy logic in the visual strategy builder (no coding required).<br/>
➡️ Validate your approach with powerful on-device backtesting and performance analytics.<br/>
➡️ Iterate quickly, compare results, and only move forward once the data supports the strategy.<br/>
➡️ Then, export your strategy as real <strong>MQL5</strong> source code and run it inside <strong>MetaTrader 5</strong>
as an Expert Advisor.

## How to export Forex Strategy Studio strategies to MetaTrader 5 (MT5)

### 1) In Forex Strategy Studio

1. Open **Forex Strategy Studio**  
   <img src="assets/images/tutorial/1.jpg" alt="Forex Strategy Studio - MetaTrader export step 1" width="320" />

2. Open the **Menu**  
   <img src="assets/images/tutorial/2.jpg" alt="Forex Strategy Studio - MetaTrader export step 2" width="320" />

3. Open **Strategy Builder**  
   <img src="assets/images/tutorial/3.jpg" alt="Forex Strategy Studio - MetaTrader export step 3" width="320" />

4. Open the strategy selector menu, and open a strategy you want to export to MetaTrader.

   > **Note**
   > The strategy should have **one Signal generator node** (a node which generates a `Signal` output), and **no infinite loops**.

   <img src="assets/images/tutorial/4.jpg" alt="Forex Strategy Studio - MetaTrader export step 4" width="320" />
   <img src="assets/images/tutorial/5.jpg" alt="Forex Strategy Studio - MetaTrader export step 5" width="320" />

5. Click the **MQL** button and select **Share**  
   <img src="assets/images/tutorial/6.jpg" alt="Forex Strategy Studio - MetaTrader export step 6" width="320" />

6. Choose a sharing service and upload the file (example: **Google Drive**)  
   <img src="assets/images/tutorial/7.jpg" alt="Forex Strategy Studio - MetaTrader export step 7" width="320" />
   <img src="assets/images/tutorial/8.jpg" alt="Forex Strategy Studio - MetaTrader export step 8" width="320" />

### 2) On your PC

1. Download the **MQL5** file from the sharing service to your PC (example: Google Drive)  
   ![Forex Strategy Studio - MetaTrader export step 9](assets/images/tutorial/9.jpg)

2. Open **MetaEditor** and select **File → Open Data Folder**, then navigate to:
   `MQL5 → Experts → Advisors`  
   ![MetaEditor - Open Data Folder](assets/images/tutorial/10.jpg)

3. Save the file to the **Expert Advisors** folder and change the extension to **.mq5**  
   ![MetaEditor - Save MQL5 file to Experts folder](assets/images/tutorial/11.jpg)

4. Open the saved file in MetaEditor and **Compile** it  
   ![MetaEditor - Compile MQL5 file](assets/images/tutorial/12.jpg)

5. Open **MetaTrader 5** and open the **Strategy Tester** (`View → Strategy Tester`)  
   ![MetaTrader 5 - Strategy Tester](assets/images/tutorial/13.jpg)

6. Configure the backtest in the Strategy Tester panel: select the Expert Advisor, set the desired parameters (Symbol, Timeframe, Date Range, etc.), and click **Start**  
   ![MetaTrader 5 - Run Expert Advisor in Strategy Tester](assets/images/tutorial/14.jpg)

7. After the backtest is complete, analyze results in the various tabs (**Graph**, **Report**, **Journal**, etc.)  
   ![MetaTrader 5 - Strategy Tester graph](assets/images/tutorial/15.jpg)
   ![MetaTrader 5 - Strategy Tester report](assets/images/tutorial/16.jpg)
   ![MetaTrader 5 - Backtest chart](assets/images/tutorial/17.jpg)