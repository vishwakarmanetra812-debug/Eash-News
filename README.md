<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>News Section</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      margin: 0;
      padding: 0;
    }
    .news-section {
      max-width: 800px;
      margin: 40px auto;
      padding: 20px;
      background: #fff;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      border-radius: 8px;
    }
    .news-section h2 {
      text-align: center;
      color: #333;
    }
    .news-list {
      list-style: none;
      padding: 0;
    }
    .news-list li {
      padding: 12px;
      border-bottom: 1px solid #ddd;
    }
    .news-list li:last-child {
      border-bottom: none;
    }
    .news-date {
      font-size: 14px;
      color: #999;
    }
    .news-title {
      font-size: 18px;
      color: #0073e6;
      text-decoration: none;
      display: block;
      margin-top: 5px;
    }
    .news-title:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="news-section">
    <h2>Latest News</h2>
    <ul class="news-list">
      <li>
        <span class="news-date">August 22, 2025</span>
        <a href="#" class="news-title">Our new website is now live!</a>
      </li>
      <li>
        <span class="news-date">August 15, 2025</span>
        <a href="#" class="news-title">Dark mode feature coming soon</a>
      </li>
      <li>
        <span class="news-date">August 10, 2025</span>
        <a href="#" class="news-title">Check out our latest blog post</a>
      </li>
    </ul>
  </div>
</body>
</html>
