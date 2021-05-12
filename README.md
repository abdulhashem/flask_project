from flask import Flask
# flask_project
# testing


app=Flask(__name__)
@app.route('/')
def hello_world():
    return "Hello, world!"
if __name__=="__main__":
    app.run()
