<template>
  <!--------Cart Section ------>
  <div class="small-container cart-page">
    <table>
      <tr>
        <th>Products</th>
        <th>Quantity</th>
        <th>Price</th>
      </tr>
      <tr>
        <td>
          <div class="cart-info">
            <img src="images/buy-1.jpg" />
            <div>
              <p>Red prited Tshirt</p>
              <small>5000</small>
              <a>Remove</a>
            </div>
          </div>
        </td>
        <td><input type="number" value="1" /></td>
        <td>5000</td>
      </tr>
      <tr>
        <td>
          <div class="cart-info">
            <img src="images/buy-2.jpg" />
            <div>
              <p>Black Shoes</p>
              <small>5000</small>
              <a>Remove</a>
            </div>
          </div>
        </td>
        <td><input type="number" value="1" /></td>
        <td>5000</td>
      </tr>
      <tr>
        <td>
          <div class="cart-info">
            <img src="images/buy-3.jpg" />
            <div>
              <p>Gray Pants</p>
              <small>5000</small>
              <a>Remove</a>
            </div>
          </div>
        </td>
        <td><input type="number" value="1" /></td>
        <td>5000</td>
      </tr>
    </table>

    <div class="total-price">
      <table>
        <tr>
          <td>Subtotal</td>
          <td>15000</td>
        </tr>
        <tr>
          <td>Tax</td>
          <td>300</td>
        </tr>
        <tr>
          <td>Total</td>
          <td>18000</td>
        </tr>
      </table>
    </div>
  </div>
</template>
