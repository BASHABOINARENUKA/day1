# day1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
  background-color: #eeeeee;
  font-family: Arial, sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  margin: 0;
}

.contaier {
  background-color: white;
  width: 280px;
  padding: 12px;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.15);
}

.image img {
  width: 100%;
  height: auto;
  border-radius: 5px;
  margin-bottom: 6px;
}

.contaier p:first-of-type {
  font-size: 14px;
  font-weight: 500;
  color: #0f1111;
  line-height: 1.2;
  margin: 0 0 3px 0;
  display: -webkit-box;

  -webkit-box-orient: vertical;
  overflow: hidden;
  text-overflow: ellipsis;
}

.rating {
  width: 85px;
  height: auto;
  margin: 0 0 6px 0;
  display: block;
}

.bought,
.delivery,
.ship {
  color: #565959;
  font-size: 13px;
  margin: 0 0 6px 0;
}

.price {
  font-size: 20px;
  font-weight: bold;
  margin: 0 0 6px 0;
  color: #0f1111;
}

.price sup {
  font-size: 12px;
  vertical-align: top;
}

.btn {
  background-color: #ffd814;
  border: 1px solid #fcd200;
  border-radius: 20px;
  width: 100%;
  padding: 10px;
  font-weight: bold;
  cursor: pointer;
  transition: background-color 0.2s ease;
  margin-top: 10px;
}

.btn:hover {
  background-color: #f7ca00;
}
    </style>
</head>
<body>
<div class="contaier">
  <div class="image">
    <img src="https://sellbroke.com/_devices/desktop/skytech/skytech-azure-2-intel-i9-14900k-rtx-4090.webp" alt="amazon_image">
  </div>

  <p>Skytech gaming Pc Desktop -Intel Core i7 1200F 2.1 GHz, NVIDIA RTX 4070 Ti, 1TB NVME SSD, 16GB DDR4 RAM 3200, 750W Gold PS...</p>

  <img class="rating" src="https://png.pngtree.com/png-vector/20220721/ourmid/pngtree-four-star-rating-sign-png-image_6026608.png" alt="rating">

  <p class="bought">50+ bought in past month</p>
  <p class="price"><sup>$</sup>1,979 <sup>59</sup></p>
  <p class="delivery">$159.58 delivery</p>
  <p class="ship">Ships to India</p>

  <button class="btn">Add to cart</button>
</div>

</body>
</html>
