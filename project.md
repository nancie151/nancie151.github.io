<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Card Layout Example</title>
<style>
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
  }
  .card img {
    max-width: 50%;
    height: auto;
    margin-bottom: 10px;
  }
  .card h2 {
    margin: 0;
  }
  .card p {
    flex-grow: 1;
    margin: 0;
  }
</style>
</head>
<body>
  <div class="card-container">
    <div class="card">
      <img src="image1.jpg" alt="Card 1 Image">
      <h2>Phishing Website Detection uding Deep Learning Neural Network Models</h2>
      <p>The impact of phishing attacks is significant, with businesses in the United States losing up to $2 billion per year as their clients fall victim to these attacks. This project aims to develop a deep learning model for detecting phishing website by extracting Uniform Resource Locator (URL) features. A diverse dataset containing labeled samples of phishing URLs and legitimate URLs will be collected and used to train the model. By analyzing and extracting URL features and patterns, the model will be trained to accurately identify and classified phishing websites.</p>
      <a href="https://github.com/nancie151/phishing-website-detection/blob/main/phishing%20website%20detection.ipynb">Github</a>
    </div>
    <div class="card">
      <img src="image2.jpg" alt="Card 2 Image">
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
