# Cross-platform Dataset

This dataset contains 1,659 comments initially collected from Twitter, Instagram, and TikTok using web scraping for sentiment analysis using IndoBERTweet.

It is a part of the research paper [*Sentiment Analysis of Comments Across Different Social Media Using IndoBERT*](https://github.com/stefani-gifta/paper-nlp-IndoBERT-2025).

## Directories

This repository consists of 4 folders, which are:

* Preprocessed comments
* Labeled comments predicted by the [original model](https://huggingface.co/ridho2401/sa-tapera)
* Labeled comments predicted by the custom model (a result of transfer learning)
* Manually labeled comments

The preprocessing, transfer learning, and labeling methods are explained in the paper.

## Constant Variable, Distribution, and Tools

The viral Indonesian hashtag **_#KaburAjaDulu_ (#JustRunAwayFirst)** was used as the constant variable to ensure consistency.

Comments distribution before and after preprocessing:
| Platform  | Before Preprocessing (Raw) | After Preprocessing |
|-----------|-----------|----------------------|
| Twitter   | 665       | 640                  |
| Instagram | 587       | 527                  |
| TikTok    | 500       | 492                  |
| **Total** | **1,752** | **1,659**            |

Scraping tools used:
- Twitter: [Tweet-Harvest](https://helmisatria.com/blog/cara-crawl-data-twitter-thread-komentar)
- Instagram: [Comments Exporter](https://chromewebstore.google.com/detail/commentsexporter/ldhjpljmgnggmkpcgaicmocfoefbcojl) (Chrome extension)
- TikTok: [Apify TikTok Scraper](https://apify.com/clockworks/free-tiktok-scraper/api)

## Citation
 
If you use this dataset, please cite:
 
```bibtex
@unpublished{ganda2025sentiment,
  title  = {Sentiment Analysis of Comments Across Different Social Media Using IndoBERT},
  author = {Ganda, Stefani Gifta and Kenni, Edeline and Sutoyo, Rhio and Jeremy, Nicholaus Hendrik},
  note   = {Undergraduate research, Bina Nusantara University},
  year   = {2025}
}
```

## Contributors

- Stefani Gifta Ganda
- Edeline Kenni

## License
 
This project is licensed under the MIT License.
