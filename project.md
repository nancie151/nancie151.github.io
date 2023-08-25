Projects 
<html>
<head>
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap" rel="stylesheet">
  <style>
    .button{
        display: inline-block;
        padding: 6px 12px;
        text-align: left;
        text-decoration: none;
        color: #ffffff;
        background-color: #c2c7c7;
        border-radius: 6px;
        outline: none;
        transition: 0.3s;
        border: 2px solid transparent;
      }
      .button:hover,
      .button:focus {
        background-color: #c2c7c7;
        border-color: #7aa8b7;
      }
    .card-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
    }

    .card {
      border: 1px solid #ccc;
      padding: 20px;
      width: calc(100% - 20px);
      box-sizing: border-box;
      margin-bottom: 20px;
      display: flex;
      flex-direction: column;
      font-family: 'Open Sans', sans-serif; /* Apply the font here */
    }

    .card img {
      max-width: 100%;
      height: auto;
      margin-bottom: 10px;
    }

    .card h2 {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
    }

    .card p {
      flex-grow: 1;
      margin: 0;
      font-family: 'Open Sans', sans-serif;
    }
  </style>
</head>
<body>
  <div class="card-container">
    <div class="card">
      <img src="https://cdn.activestate.com/wp-content/uploads/2021/02/phishing-detection-with-Python.jpg" alt="Card 1 Image">
      <h2 style="font-size: 13px; color:black; font-weight: bold;">Phishing Website Detection using Deep Learning Neural Network Models</h2>
      <p style="font-size: 12px; color: black;">The impact of phishing attacks is significant, with businesses in the United States losing up to $2 billion per year as their clients fall victim to these attacks. This project aims to develop a deep learning model for detecting phishing websites by extracting Uniform Resource Locator (URL) features. A diverse dataset containing labeled samples of phishing URLs and legitimate URLs will be collected and used to train the model. By analyzing and extracting URL features and patterns, the model will be trained to accurately identify and classify phishing websites.</p>
    <a class="button" href="https://www.w3docs.com/learn-html/html-button-tag.html"><span>Github</span></a>
    </div>
    <div class="card">
      <img src="image9.jpg" alt="Card 2 Image">
      <h2>Card 2</h2>
      <p>This is the content of card 2. Ut enim ad minim veniam...</p>
      <a href="https://example.com/card2">Learn More</a>
    </div>
         <div class="card">
      <img src="image9.jpg" alt="Card 9 Image">
      <h2>Card 9</h2>
      <p>This is the content of card 9. Sed ut perspiciatis unde omnis iste...</p>
      <a href="https://example.com/card9">Learn More</a>
    </div>
    <div class="card">
      <img src="image10.jpg" alt="Card 10 Image">
      <h2>Card 10</h2>
      <p>This is the content of card 10. Nemo enim ipsam voluptatem quia...</p>
      <a href="https://example.com/card10">Learn More</a>
    </div>
  </div>
</body>
</html>
