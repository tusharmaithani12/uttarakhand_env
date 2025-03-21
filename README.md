git clone https://github.com/tusharmaithani12/uttarakhand_env.git && cd uttarakhand_env && \
python -m venv env && source env/bin/activate && \  # For Windows: env\Scripts\activate
pip install -r requirements.txt && \
jupyter notebook Main.ipynb
