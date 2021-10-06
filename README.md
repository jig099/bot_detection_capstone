# Capstone project - bot detection
## Paper reviews
1. [Detecting Bot Behaviour in Social Media using Digital DNA Compression](http://ceur-ws.org/Vol-2563/aics_35.pdf)
   - Assuming that bot behave less randomly comparing to humans, the paper measures the randomness and unpredictability in the posting behavior via a lossless compression algorithm on the Digit DNA sequence of the account
   - Steps:
      - Represent account with Digit DNA
      - Deploy a lossless compression on the Digit DNA
      - Based on the compression statistics, differentiate real users from bots via ML alg
2. [BotCamp: Bot-driven Interactions in Social Campaigns](https://www.cs.unm.edu/~nabuelrub/BotCamp/)
3. [TweepFake: about detecting deepfake tweets](https://arxiv.org/abs/2008.00036)
## Datasets
1. [Data without bot labeling](https://ucla.app.box.com/s/nk27vfb26jfhqrvyfv9e8m3dvbz11sq1)
2. [TIMME](https://github.com/PatriciaXiao/TIMME/tree/master/data/P_all)
3. [Botcamp us election](https://github.com/PatriciaXiao/TIMME/tree/master/data/P_all)
## Useful Resource
1. [BERT text classifier](https://github.com/PatriciaXiao/Transformers_Compare/tree/main/examples/classifier)
