# Taiwan-stock-and-Kelly-formula-reaearch
  This research began from November 2017.
  The data is originated from Taiwan Economical Journal, including 93 taiwanese public campanies.
  Input 240 trading days to predict the next 10 days' variation, with variable categories(9, 10, 12version).

  Using python to program this CNN 2d model for calculating short-term future stock fluctuating tendency.
  We predicted the distribution of future stock tendency collaborating with Kelly formula, by deep learning CNN 2D model.
  As the interval of future fluctuation is much reasonable to predict and suitable for the Kelly.F, we set the output in a distribution of these intervals. Also, we decided the interval based on the distribution of real data.
  Maximized trading performance by deducing the extreme of trading function in Kelly.F with differential. In mathematics, given a calculated win rate and odds in specific game, we can optimized capital allocation to gain the highest reward in the long run.  
  Since the huge institutuin influences on the stock price and we decided to add and normalized their net buy/sell to mitigated the impact of institutional investors.
  We use add regularizers and normalizing input to cooperate with Xelu which maintaining the stability of training.
