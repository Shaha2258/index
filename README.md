<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./css/icofont.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&family=Moon+Dance&family=Poppins:wght@100;400;500;600;700&display=swap"
     rel="stylesheet">
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="style.css">
    <title>NextGenCode.Net</title>
    </head>
  <body>

     <nav>
      <div class="container">
        <img src="img/invest.jpg" class="nav-img-logo">
        <div class="search-bar">
          <span class="material-icons">search</span>
          <input type="search" placeholder="Search">
        </div>
        <div class="profile-area">
          <div class="theme-btn">
            <span class="material-icons active">light_mode</span>
            <span class="material-icons">dark_mode</span>
          </div>
          <div class="profile">
            <div class="profile-photo">
              <img src="img/mypic.jpg">
            </div>
             <h5>Chu Hua</h5>
             <span class="material-icons">expand_more</span>
          </div>
          <button id="menu-btn">
            <span class="material-icons">menu</span>
          </button>
        </div>
      </div>
     </nav>
 <!--end navbar-->
 <main>
  <aside>
    <button id="close-btn">
      <span class="material-icons">close</span>
    </button>

    <div class="sidebar">
      <a href="" class="active">
        <span class="material-icons">dashboard</span>
        <h4>Dashboard</h4>
      </a>
      <a href="">
        <span class="material-icons">currency_exchange</span>
        <h4>Exchange</h4>
      </a>
      <a href="">
        <span class="material-icons">account_balance_wallet</span>
        <h4>Wallet</h4>
      </a>
      <a href="">
        <span class="material-icons">payment</span>
        <h4>Transections</h4>
      </a>
      <a href="">
        <span class="material-icons">pie_chart</span>
        <h4>Analytics</h4>
      </a>
      <a href="">
        <span class="material-icons">message</span>
        <h4>Messages</h4>
      </a>
      <a href="">
        <span class="material-icons">help_center</span>
        <h4>Help Center</h4>
      </a>
      <a href="">
        <span class="material-icons">settings</span>
        <h4>Settings</h4>
      </a>
    </div>
    <!-----end of sidebar------>

    <div class="updates">
       <span class="material-icons">update</span>
       <h4>Updates Available</h4>
       <p>Security Updates</p>
       <p>General Updates</p>
       <a href="#">Updates Now</a>
    </div>
  </aside>
  <!--end of aside-->

  <section class="middle">
    <div class="header">
       <h1>Overview</h1>
       <input type="date">
    </div>

    <div class="cards">
       <div class="card">
          <div class="top">
            <div class="left">
              <img src="img/btc.jpg" class="btc">
              <h2>BTC</h2>
            </div>
            <img src="img/visa1.jpg" class="right">
          </div>
          <div class="middle">
            <h1>$545.256</h1>
            <img src="img/cardchip.png" class="chip">
          </div>
          <div class="bottom">
            <div class="left">
              <small>Card Holder</small>
              <h5>John Dou</h5>
            </div>
            <div class="right">
                <div class="Expiry">
                   <small>Expiry</small>
                   <h5>08/23</h5>
               </div>
               <div class="cvv">
                <small>CVV</small>
                <h5>123</h5>
            </div>
            </div>
          </div>
       </div>
        <!----end of card-1---->

        <div class="card">
          <div class="top">
            <div class="left">
              <img src="img/eth.png" class="eth">
              <h2>ETH</h2>
            </div>
            <img src="img/visa1.jpg" class="right">
          </div>
          <div class="middle">
            <h1>$545.256</h1>
            <img src="img/cardchip.png" class="chip">
          </div>
          <div class="bottom">
            <div class="left">
              <small>Card Holder</small>
              <h5>John Dou</h5>
            </div>
            <div class="right">
                <div class="Expiry">
                   <small>Expiry</small>
                   <h5>08/23</h5>
               </div>
               <div class="cvv">
                <small>CVV</small>
                <h5>123</h5>
            </div>
            </div>
          </div>
       </div>
        <!----end of card-2---->

        <div class="card">
          <div class="top">
            <div class="left">
              <img src="img/btc.jpg" class="btc">
              <h2>BTC</h2>
            </div>
            <img src="img/visa1.jpg" class="right">
          </div>
          <div class="middle">
            <h1>$545.256</h1>
            <div class="chip">
            <img src="img/cardchip.png" class="chip">
          </div>
          </div>
          <div class="bottom">
            <div class="left">
              <small>Card Holder</small>
              <h5>John Dou</h5>
            </div>
            <div class="right">
                <div class="Expiry">
                   <small>Expiry</small>
                   <h5>08/23</h5>
               </div>
               <div class="cvv">
                <small>CVV</small>
                <h5>123</h5>
            </div>
            </div>
          </div>
       </div>
        <!----end of card-3---->
    </div>
    <!----end of cards----->

    <div class="monthly-report">
        <div class="report">
            <h3>Income</h3>
            <div>
              <details>
                <h1>$29.025</h1>
                <h6 class="text-success">+3.5%</h6>
              </details>
              <p class="text-muted">Compared to $26,938 last month</p>
            </div>
        </div>
        <!--=== end of income report ==-->
        <div class="report">
          <h3>Expenses</h3>
          <div>
            <details>
              <h1>$29.025</h1>
              <h6 class="text-danger">-6.5%</h6>
            </details>
            <p class="text-muted">Compared to $11,938 last month</p>
          </div>
      </div>
      <!--=== end of expenses report ==-->
      <div class="report">
        <h3>Cashback</h3>
        <div>
          <details>
            <h1>$9.025</h1>
            <h6 class="text-success">-17.5%</h6>
          </details>
          <p class="text-muted">Compared to $118,938 last month</p>
        </div>
    </div>
  <!--=== end of cash report ==-->
    <div class="report">
      <h3>Income</h3>
      <div>
        <details>
          <h1>$29.025</h1>
          <h6 class="text-danger">+3.5%</h6>
        </details>
        <p class="text-muted">Compared to $26,938 last month</p>
      </div>
  </div>
  <!--=== end of turnover report ==-->
    </div>

    <!--==== end of monthly report ====-->

    <div class="fast-payment">
       <h2>Fast Payment</h2>
       <div class="badges">
       <div class="badge">
          <span class="material-icons">add</span>
        </div>
        <div class="badge">
             <span class="bg-primary"></span>
        <div>
              <h5>Training</h5>
              <h4>$50</h4>
          </div>  
          </div>
      <div class="badge">
        <span class="bg-success"></span>
           <div>
           <h5>Internet</h5>
           <h4>$70</h4>
      </div>  
      </div>
       <div class="badge">
        <span class="bg-primary"></span>
      <div>
           <h5>Gas</h5>
           <h4>$40</h4>
       </div>  
       </div>
       <div class="badge">
       <span class="bg-danger"></span>
       <div>
           <h5>Movies</h5>
           <h4>$90</h4>
       </div>  
       </div>
       <div class="badge">
       <span class="bg-info"></span>
       <div>
           <h5>Education</h5>
           <h4>$990</h4>
       </div>  
       </div>
       <div class="badge">
       <span class="bg-warning"></span>
       <div>
           <h5>Electricity</h5>
           <h4>$150</h4>
       </div>  
       </div>
       <div class="badge">
       <span class="bg-primary"></span>
       <div>
          <h5>Food</h5>
          <h4>$250</h4>
       </div>  
       </div>
      
       </div>
    </div>
    <!--======= end of fast payment ========-->

    <canvas id="chart"></canvas>

   </section>
   <!--end of middle-->

   <section class="right">

   </section>
   <!--end of middle-->
   </main>
   <!---------end of aside----------->

   <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.0/chart.min.js"
      integrity="sha512-7U4rRB8aGAHGVad3u2jiC7GA5/1YhQcQjxKeaVms/bT66i3LVBMRcBI9KwABNWnxOSwulkuSXxZLGuyfvo7V1A=="
      crossorigin="anonymous" referrerpolicy="no-referrer"></script>
      <script src="main.js"></script>
   <script src="js/bootstrap.bundle.js"></script>
  </body>
  </html>
