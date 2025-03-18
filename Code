# Import required libraries
import nltk
from nltk.tokenize import word_tokenize
from nltk.corpus import stopwords
# ---------------------------------------------------------------------------------------------------------------- If
# you don't want to run nltk.download() every time you execute your script, you can pre-download the NLTK resources
# and ensure they are available in the correct directory. Once the resources are downloaded, NLTK will automatically
# detect them, and you won't need to call nltk.download() again.
# ----------------------------------------------------------------------------------------------------------
# nltk.download('punkt')
# nltk.download('stopwords')
# Sample text
text = "A cat sat on the mat.."
print("Text for example:", text)
# 1) Tokenization: Breaking text into smaller pieces
tokens = word_tokenize(text)
print("Tokenized Text:", tokens)
# 2) Normalization: Lowercasing & Removing Punctuation
normalized_tokens = [word.lower() for word in tokens if word.isalnum()]
print("Normalized Text:", normalized_tokens)
# 3) Stop Word Removal: Cutting Out the Noise
stop_words = set(stopwords.words('english'))
filtered_tokens = [word for word in normalized_tokens if word not in stop_words]
print("Filtered Text (Stop Words Removed):", filtered_tokens)
