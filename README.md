# toolbox
Curated libraries for a faster workflow

# Phase: Data
## Annotation
- Annotate Image: [makesense.ai](https://www.makesense.ai/) 
- Annotate Text: [doccano](https://doccano.herokuapp.com/), [prodigy](https://prodi.gy/)

## Dataset
- NLP: [nlp-datasets](https://github.com/niderhoff/nlp-datasets)
- swear-words: [curse-words](https://github.com/reimertz/curse-words), [badwords](https://github.com/MauriceButler/badwords), [LDNOOBW](https://github.com/LDNOOBW/List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words)
- A text file containing over 466k English words: [english-words](https://github.com/dwyl/english-words)
- Image: [1 million fake faces](https://archive.org/details/1mFakeFaces)

## Fetch data
- Manipulate audio with a simple and easy high level interface: [pydub](https://github.com/jiaaro/pydub)
- Download YouTube vidoes: [pytube](https://github.com/nficano/pytube)
- Manipulate Google Sheets with Python: [gspread](https://github.com/burnash/gspread)
- Auto fetch images from web for certain search: [py-image-dataset-generator](https://github.com/tomahim/py-image-dataset-generator)
- Python API for datasets: [pydataset](https://github.com/iamaziz/PyDataset)
- News crawler: [news-please](https://github.com/fhamborg/news-please)

## Data Augmentation
- Text data: [nlpaug](https://github.com/makcedward/nlpaug)
- Image: [imgaug](https://github.com/aleju/imgaug/), [albumentations](https://github.com/albumentations-team/albumentations), [augmentor](https://github.com/mdbloice/Augmentor)

# Phase: Exploration

## Clean data
- Missing data visualization module for Python: [missingno](https://github.com/ResidentMario/missingno)

## Experiment in notebooks
- View Jupyter notebooks through CLI: [nbdime](https://github.com/jupyter/nbdime)
- Parametrize notebooks: [papermill](https://github.com/nteract/papermill)
- Access notebooks programatically: [nbformat](https://nbformat.readthedocs.io/en/latest/api.html)
- Convert notebooks to other formats: [nbconvert](https://nbconvert.readthedocs.io/en/latest/)
- Extra utilities not present in frameworks: [mlxtend](https://github.com/rasbt/mlxtend)

# Phase: Feature Engineering
## Generate Features
- Automatic feature engineering: [featuretools](https://github.com/FeatureLabs/featuretools), [autopandas](https://autopandas.io/)

# Phase: Modeling
## Model Selection
- Bruteforce through all scikit-learn model and parameters: [hungabunga](https://github.com/ypeleg/HungaBunga)
- Autogenerate ML code: [automl-gs](https://github.com/minimaxir/automl-gs)

## NLP
- Text generation: [gp2client](https://github.com/rish-16/gpt2client), [textgenrnn](https://github.com/minimaxir/textgenrnn)
- Text summarization: [textrank](https://github.com/summanlp/textrank), [pytldr](https://github.com/jaijuneja/PyTLDR)
- Spelling correction: [JamSpell](https://github.com/bakwc/JamSpell), [pyhunspell](https://github.com/blatinier/pyhunspell), [pyspellchecker](https://github.com/barrust/pyspellchecker), [cython_hunspell](https://github.com/MSeal/cython_hunspell), [hunspell-dictionaries](https://github.com/wooorm/dictionaries)
- Keyword extraction: [rake](https://github.com/zelandiya/RAKE-tutorial), [pke](https://github.com/boudinfl/pke)
- Multiply Choice Question Answering: [mcQA](https://github.com/mcQA-suite/mcQA)
- Sequence to sequence models: [headliner](https://github.com/as-ideas/headliner)
- Transfer learning: [finetune](https://github.com/IndicoDataSolutions/finetune)
- Translation: [googletrans](https://pypi.org/project/googletrans/)
- Embeddings: [pymagnitude (manage vector embeddings easily)](https://github.com/plasticityai/magnitude), [chakin (download pre-trained word vectors)](https://github.com/chakki-works/chakin)
- Inflections: [inflect](https://pypi.org/project/inflect/)
- Contractions: [pycontractions](https://pypi.org/project/pycontractions/)
- Clustering: [spherecluster (kmeans with cosine distance)](https://github.com/jasonlaska/spherecluster)
- String matching: [jellyfish (perform string and phonetic comparison)](https://pypi.org/project/jellyfish/),[flashtext (superfast extract and replace keywords)](https://github.com/vi3k6i5/flashtext), [pythonverbalexpressions: (verbally describe regex)](https://github.com/VerbalExpressions/PythonVerbalExpressions), [commonregex (readymade regex for email/phone etc)](https://github.com/madisonmay/CommonRegex)
- Create wordclouds: [stylecloud](https://github.com/minimaxir/stylecloud)

## RecSys
- Factorization machines (FM), and field-aware factorization machines (FFM): [xlearn](https://github.com/aksnzhy/xlearn)

## Computer Vision
- Segmentation Models in Keras: [segmentation_models](https://github.com/qubvel/segmentation_models)

## Timeseries
- Predict Time Series: [prophet](https://facebook.github.io/prophet/docs/quick_start.html#python-api)

# Phase: Monitoring
## Monitor training process
- Learning curve: [lrcurve (plot realtime learning curve in Keras)](https://github.com/AndreasMadsen/python-lrcurve), [livelossplot](https://github.com/stared/livelossplot)
- Notifications: [knockknock (get notified by slack/email)](https://github.com/huggingface/knockknock), [jupyter-notify (notify when task is completed in jupyter)](https://github.com/ShopRunner/jupyter-notify)

# Phase: Optimization
## Hyperparameter Optimization
- Keras: [keras-tuner](https://github.com/keras-team/keras-tuner)

## Interpretability
- Visualize keras models: [keras-vis](https://github.com/raghakot/keras-vis)

## Visualization
- Draw CNN figures: [nn-svg](http://alexlenail.me/NN-SVG/LeNet.html)

# Phase: Production
## Scalability
- Parallelize .apply in Pandas: [pandarallel](https://github.com/nalepae/pandarallel), [swifter](https://github.com/jmcarpenter2/swifter)

## Bechmarking
- Profile pytorch layers: [torchprof](https://github.com/awwong1/torchprof)

## API
- Read config files: [config](https://pypi.org/project/config/)
- Validate JSON in Flask: [schema](https://github.com/keleshev/schema), [jsonschema](https://pypi.org/project/jsonschema/)
- Enable CORS in Flask: [flask-cors](https://flask-cors.readthedocs.io/en/latest/)
- Cache results of functions: [cachetools](https://pypi.org/project/cachetools/)

## Adversarial testing
- Generate images to fool model: [foolbox](https://github.com/bethgelab/foolbox)

## Python libraries
- Datetime compatible API for Bikram Sambat: [nepali-date](https://github.com/arneec/nepali-date)
- bloom filter: [python-bloomfilter](https://github.com/jaybaird/python-bloomfilter)
- Run python libraries in sandbox: [pipx](https://github.com/pipxproject/pipx)
- Open remote files directly: [smart_open](https://github.com/RaRe-Technologies/smart_open)
- Pretty print tables in CLI: [tabulate](https://pypi.org/project/tabulate/)
