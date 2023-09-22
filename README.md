# English to Hinglish Translator

This is a simple Python script that translates English text to Hinglish. 
It retains certain English words while converting the rest to Hinglish, making it useful for bilingual communication.

## Usage

1. Clone the repository to your local machine:

git clone https://github.com/charan-teja2003/english-to-hinglish.git


2. Install the required dependencies:

!pip install -qU \
  transformers \
  sentence-transformers\
  accelerate\
  einops \
  xformers


3. Run the translator script:

python English_to_Hinglish.py


4. Input English text, and the script will generate the corresponding Hinglish translation.

# Configuration

You can customize the translation by adding or modifying English-to-Hinglish mappings in the 'english_to_hinglish' dictionary within the 'English_to_Hinglish.py' file.

# Example

Input (English):

I had about a 30 minute demo just using this new headset.

 मैं 30 minute demo था सिर्फ इस नए headset का इस्तेमाल

## License

This project is licensed under the MIT License.

## Acknowledgments

- This project uses the Hugging Face Transformers library for machine translation.

Feel free to modify and improve this script as needed for your specific use case. Happy translating!


