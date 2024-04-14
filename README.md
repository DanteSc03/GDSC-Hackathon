# [Cadeira](https://www.linkedin.com/company/cadeira-ia) Chatbot

Cadeira Chatbot is designed to optimize reservations for all types of restaurants. We have an interactive database through sql and duckling allowing for all types of time requests. 

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install ChatbotRasa.

```bash
pip install ChatbotRasa
pip install spacy
python -m spacy download en_core_web_md

```

## Usage

```python
import ChatbotRasa

# Run the actions Server
rasa run actions

# Run the docker image to allow for duckling entity extraction
on mac M1/M2: docker run --platform linux/amd64 -p 8000:8000 rasa/duckling

on mac Intel: docker run -p 8000:8000 rasa/duckling

on windows: docker run -p 8000:8000 rasa/duckling

# Setting Duckling to correct timezone
Make sure to set the timezone correctly in the duckling pipeline
    timezone: "Europe/Madrid" (Current Setting)
  
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Contact
[Juan Carlos Mezquita Lobato](https://www.linkedin.com/in/carlosmezquitalobato/)

[Dante Mathieu Schrantz](https://www.linkedin.com/in/dante-m-schrantz/)

[Miguel Diaz Perez de Juan](https://www.linkedin.com/in/migueldiazperezdejuan/)

## License
[Private use](https://www.youtube.com/watch?v=10GjJIO8I2Q)
