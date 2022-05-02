# Personal Portfolio website

Light and Dark Theme Personal Portfolio Website written using Flask Framework in Python.

## Screenshots
- Light Theme Cropped

  ![Light Theme Cropped](https://github.com/dmdhrumilmistry/Flask-Portfolio/blob/main/.images/Light-Homepage-Crop.png?raw=True)
  
- Light Theme

  ![Light Theme](https://github.com/dmdhrumilmistry/Flask-Portfolio/blob/main/.images/Light-Homepage.png?raw=True)

- Dark Theme

  ![Dark Theme](https://github.com/dmdhrumilmistry/Flask-Portfolio/blob/main/.images/Dark-Homepage.png?raw=True)

## Technologies Used
- Frontend
    - HTML
    - CSS
    - JS

- Backend
    - Python
    - sqlite3

## Installation
- Install pre-requirements
    - git
    - Python 3.X

- Clone repo
    ```bash
    git clone --depth=1 https://github.com/dmdhrumilmistry/Flask-Portfolio
    ```

- Change directory
    ```bash
    cd Flask-Portfolio
    ```

- Install Project requirements
    ```bash
    python -m pip install -r requirements.txt
    ```
    > `Note`: Ubuntu users might have to use `python3` instead of `python`

- Make Database migrations
    ```bash
    flask db init
    flask db migrate -m "initial migration"
    flask db upgrade
    ```

- run application using wsgi server
    ```bash
    waitress-serve wsgi:app
    ```

## Deploy using Docker
- Build image
  ```bash
  docker build -t flask-portfolio .
  ```
- Run image
  ```bash
  docker run -d -p 8080:8080 flask-portfolio
  ```

## TODO
- [ ] Make Website Responsive
- [ ] Create Blogs
