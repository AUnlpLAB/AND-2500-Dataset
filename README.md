# AND-2500
This repository hosts a curated Assamese News Classification Dataset, developed to address the scarcity of high-quality, structured resources for low-resource Indic languages. The dataset comprises 2,500 news articles, meticulously collected to facilitate research in Natural Language Processing, text classification etc. All news articles in the dataset are written in Assamese script.

# Data Collection & Methodology
The corpus was constructed using a hybrid methodology combining manual collection and web scraping. Sources include leading Assamese newspapers and digital news platforms, ensuring a linguistic style that reflects authentic modern usage. 

**Data Acquisition**: The news articles were gathered from leading Assamese newspapers and news portals. The process involved both automated web scraping scripts and manual data entry to ensure high-quality text extraction. The primary data sources- includes Assamese ePapers viz. Dainik Janambhumi (দৈনিক জনমভূমি) and Amar Asom (আমাৰ অসম), and online news portals viz. Asomia Pratidin (অসমীয়া প্ৰতিদিন), Dainandin Barta (দৈনন্দিন বাৰ্তা), Niyomia Barta (নিয়মীয়া বাৰ্তা) and News18 Assam.

**Annotation Process**: The labeling process was strictly guided by the International Press Telecommunications Council (IPTC) Subject Codes. This ensures that the categorization aligns with global media standards, facilitating cross-lingual comparison and standardization in text classification research.

# Dataset Structure
To support rich metadata analysis, each entry in the dataset includes the following attributes:

**Content**: News Headline, News Body

**Metadata**: Date of Publication(DoP), News Source, Website Link

**Target Label**: Category

**No. of tokens**: 259,177

# Categories
The dataset is classified into 20 distinct categories. These categories cover a wide spectrum of topics that includes:

‘Accident (দুৰ্ঘটনা)’, ‘Agriculture (কৃষি)’, ‘Architecture (স্থাপত্যকলা)’, ‘Crime, law and justice (অপৰাধ-আইন-ন্যায়)’, ‘Culture (সংস্কৃতি)’, ‘Disaster (দুৰ্যোগ)’, ‘Economy, business and finance (অৰ্থনীতি-ব্যৱসায়-বিত্ত)’, ‘Entertainment (মনোৰঞ্জন)’, ‘Examination (পৰীক্ষা)’, ‘Festival (উৎসৱ)’, ‘Health (স্বাস্থ্য)’, ‘Literature (সাহিত্য)’, ‘Lifestyle (জীৱনশৈলী)’, ‘Politics (ৰাজনীতি)’, ‘Social issue (সামাজিক সমস্যা)’, ‘Social media (সামাজিক মাধ্যম)’, ‘Sports (ক্ৰীড়া)’, ‘Technology (প্ৰযুক্তি)’, ‘Weather (বতৰ)’ and ‘Wildlife (বন্যপ্ৰাণী)’.

# Dataset Applications
This dataset is suitable for various NLP tasks, including but not limited to:

**Text Classification**: Training models to automatically categorize Assamese news.

**Topic Modeling**: Discovering abstract topics within the corpus.

**Headline Generation**: Summarization tasks using the article body and headline.

**Low-Resource Language Studies**: Contributing to the development of language models for Indic languages.

# Contributors of the dataset

1) **Pragyat Jyoti Baruah** [email- pragyat.jyoti.baruah@aus.ac.in]
2) **Tirthanka Borah** [email- tirthanka.borah@aus.ac.in]
