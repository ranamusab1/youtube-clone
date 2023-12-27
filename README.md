<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <!-- Material Icons -->

    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet" />
    <!-- CSS File -->
    <link rel="stylesheet" href="style.css" />
    <title>Final - Youtube UI Clone</title>
  </head>
  <body>
    <!-- Header Starts -->
    <div class="header">
      <div class="header__left">
        <i id="menu" class="material-icons">menu</i>
        <img
          src="https://youtube.com/shorts/dulaTFa7-fw?si=Ag0fa3mCAIbgPLFV"
          alt=""
        />
      </div>

      <div class="header__search">
        <form action="">
          <input type="text" placeholder="Search" />
          <button><i class="material-icons">search</i></button>
        </form>
      </div>

      <div class="header__icons">
        <i class="material-icons display-this">search</i>
        <i class="material-icons">videocam</i>
        <i class="material-icons">apps</i>
        <i class="material-icons">notifications</i>
        <i class="material-icons display-this">account_circle</i>
      </div>
    </div>
    <!-- Header Ends -->

    <!-- Main Body Starts -->
    <div class="mainBody">
      <!-- Sidebar Starts -->
      <div class="sidebar">
        <div class="sidebar__categories">
          <div class="sidebar__category">
            <i class="material-icons">home</i>
            <span>Home</span>
          </div>
          <div class="sidebar__category">
            <i class="material-icons">local_fire_department</i>
            <span>Trending</span>
          </div>
          <div class="sidebar__category">
            <i class="material-icons">subscriptions</i>
            <span>Subcriptions</span>
          </div>
        </div>
        <hr />
        <div class="sidebar__categories">
          <div class="sidebar__category">
            <i class="material-icons">library_add_check</i>
            <span>Library</span>
          </div>
          <div class="sidebar__category">
            <i class="material-icons">history</i>
            <span>History</span>
          </div>
          <div class="sidebar__category">
            <i class="material-icons">play_arrow</i>
            <span>Your Videos</span>
          </div>
          <div class="sidebar__category">
            <i class="material-icons">watch_later</i>
            <span>Watch Later</span>
          </div>
          <div class="sidebar__category">
            <i class="material-icons">thumb_up</i>
            <span>Liked Videos</span>
          </div>
        </div>
        <hr />
      </div>
      <!-- Sidebar Ends -->

      <!-- Videos Section -->
      <div class="videos">
        <h1>Recommended</h1>

        <div class="videos__container">
          <!-- Single Video starts -->
          <div class="video">
            <div class="video__thumbnail">
              <img src="https://img.youtube.com/vi/PpXUTUXU7Qc/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img src="data:image/jpeg;base64,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" alt="" />
              </div>
              <div class="title">
                <h3>
                  Top 5 Programming Languages to Learn in 2021 | Best Programming Languages to Learn
                </h3>
                <a href="">FutureCoders</a>
                <span>10M Views • 3 Months Ago</span>
              </div>
            </div>
          </div>
          <!-- Single Video Ends -->

          <!-- Single Video starts -->
          <div class="video">
            <div class="video__thumbnail">
              <img src="https://img.youtube.com/vi/YpTmcCBBdTE/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBw8NDQ0QDRAODQ0NEA8QDQ4NDw8NDw8OFhEWGBUVFRUYHykgGBoxGxUYIjEhJSk3Oi4wFx8zODMsNygyLysBCgoKDg0OGxAQGjUmHyUtLTI3NzctMi0uNS8rLS0rLzc3LS0rLTIvOC01LS0tMCs3LS0tNTUtKzEyNS01LTcrLf/AABEIAKwBJQMBIgACEQEDEQH/xAAcAAEBAAMBAQEBAAAAAAAAAAAAAQMEBgcCBQj/xABCEAACAQMCBAIECgcHBQAAAAAAAQIDBBEFEgYhMUETURQiYYEHFzJCYnGRkrHRFiNSU8HS8BUkQ1SCwuEzNKGisv/EABoBAQADAQEBAAAAAAAAAAAAAAADBAUGAgH/xAAsEQEAAgIBAgUDAgcAAAAAAAAAAQIDBBESIRMxQaGxFSJRMkIFFHGBkeHw/9oADAMBAAIRAxEAPwDx8AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAUAQFAAFAEBQBAUAQFAEAKB8gAAAAAAAAAAAAAAAAAAAAAAAAFAhQAAKAAKAICgCFBQICgCAoAgKQCFBQMYAAAAAAAAAAAAAAfdGjKpOMKcZTnNqMIRWZSk+iSAUKMqk4wpxlOc2owhFZlKT6JI9J0v4NKTowd5VrKu+c40JU1CH0cuLy/afqcF8Jw0+Hi1sTvJr1pdY0Yv5kP4vv9R1W41NfTiI5yQxdrfmbdOKe35cZ8Wdj+9u/v0v5B8Wdj+9u/v0v5Ds9x+JxTxLS02jmWJ15p+DRzhyf7UvKK8/cT2wYaxzMK1NnYvbpraeXF8VcMaZptHdKrdVK80/Ao+JSTk/2pepyivP3HCI2tRvqt1WnWryc6s3zfRJdoxXZLsjWMjLetrfbHEN7DS1K8XnmQ/a0TTbeU4+nOrCnPluouKlT9sk08r2L/gx6fYbcTqL1vmxfb2v2m80aWroduvJH9kWbL+2rsYfBvYySca11KMkmmqlFpp9GnsL8Wtl+9u/v0v5D87hbiR2rVKs27Zvk+rot919HzXvPQoVFJJxacWk00000+jTLE6uKP2sjLn2Mc8TaXH/FrZfvbv79L+Q4/jDhKenSU6blVtJtKNR4cqcv2Z45fU+/Tr19i3GO4pQqwlCpFTpzTjOElmMovqmiLJp47V4iOJMW/lrbm08w/nwp03GPCstPn4lLdOzm/Vk+cqUn0hN/hLv069eaMm9JpPTZvY8lcleqvkgKDw9oCgCFAAEKAICgCAoAxAAAAAAAAAAAAAPujRlUnGFOMpzm1GEIrMpSfZHrfBnCkbCHiVcTu5r1pdY0ov5kP4vv9RzfwY1bRVKiksX0s+HKeMOljmqflLz817M49H3Gro69ZjxJ7z8MX+I7V+rwo7R8/wCmTIyY9xJt4e3G7D27k2s9s47GlwyeX5XFHElLTqOZYnXmn4NHPOT/AGpeUV5+48e1C+q3VadavJzqTfNvkkuyS7JdkbPEULpXdX07LuG8t/NcPmuH0PL88n5xg7Oe2S3E9oj0dJp61cVeY7zPqH7Om6btxOovW6xi+3tftMmk6XtxUqr1usIv5vtftP1GjV0P4dxxlyx/SHrLm/bVgaPiSM0kYLmrGnFyl7l3b8kamTisTM+StEc+TBcVFCOZe5d2z9LhHjGVrPwrl5tJv1X1du33XnHzXvXkcrcV5VJZfuXZIxnO7G9a1+adoj3Wv5alqdN/V7/CopJSi1KMknGUXlNPo0y5OL+DendRt5Os8WkudtCae/rzlHyh7O/VYXXsNxp4reJSLccOdzU8O80554WvSjUhKFSKnCacZxksxlF9U0eTcX8LSsJ+JSzO0m/Vk+cqUn0hN/hLv0fPr6xuNbUq1GFCq7nZ4G1qrvWYuL7Y7/UR7GvXJXv/AJS6uzbDft3ifR4aDNdum6tR0FONFyfhRqPdNQzyTf8AXv6mIwJdLHdAUB9QFAEBQBAUAQFAGAAAAAAAAAAAAAB9Qm4tSi3GUWnGUW04yXRp9meocG8Wq8SoXDUbuK9WXSNeK7ryl5r3rul5afUJOLUotxlFpxlF4aa6NPsyfBnthtzHkr7OtXPXifP0l73uG45Lg/ipXaVG4ajdRXqvklXSXVeUvNe9d8dTk6DFkrkr1VcxmxXxW6beb83iPQqWoUdk/VqQy6NVLMoS/jF91/E4Kz4fnbVH6Sl4kW9kU90cZ5TT7+z8+np+TV1CyjXhiXKS+RLvF/keqYMXixkvHl/3ssa27bHHRM/b8OKkjG0bl1bypTcZrDX2Nea9ho3leNKDlN8uy7t+SNS81rXqmezTr93kw3VeNKLlLp2XdvyRzl1cSqy3S9y7JFu7mVae6X+mK6RRhOT3t6c9umv6flexYunvPmh2HBvCnpG24uo/3dc6VKX+N9KX0PZ876us4O4W8fbcXUf1HWlSf+N5Sl9D8fq6+i5PenpdX33jt6Qzt/f6eceOe/rLImNxjyYbu7p0KcqlWShTgsyk/wCub9hrTxEcyw45meIZLy7p0Kc6lWShTgsyk+35v2HlXE/ENTUKneFvB/qqX+6fnL8PtbcS8QVL+p3hbwf6qn/ul5y/D/y/xTE29vxJ6a+Xy6HR0vCjrv8Aq+AApQaSAoAgKAICgCAoA+QUAa4AAAAAAAAAAAACgFAsJOLTi3GUWnGUW01JdGn2Z3Gncf7aUY3FKdSrHlKpTcIqa7Np9H54/wCDhwTYs98U80lBm18eaOLw9B+MGj/l633qf5j4waP+Xrfep/meflJ/qGf8+yv9N1/x7y7a/wCNLevHErespL5Mt1PKf29Dkb27lXnul/piukV7PzNcp4y7mbLXotbssYdfHhjikBuaVVoU6qnc051qceapQ2pSl9LPWPs7/V11AVqzxPKa1eqOHffp/R/y9b71P8y/p/R/cVvvU/zOBBc+oZ/z7Qo/Tdf8e8u+/T+j+4rfep/mc1xHr9S/ms5p0If9OlnPP9qXnL8Ptz+OCPJt5clem09kuLSw4rdVY7gKCstIUAACgCAoAgKAIQoAgKANUAAAAAAAAAACgoHb/Bjo9rqb1OyrUqcruraTqafWnndSrRynjn5zg8fRZ6L8Wul77JxjSdPSt9LWU28XEvQ4TUqntzKEuXabX1eG6XqNezrQr2tSVCvT3bKkMZW6Li+TTT5N9TfXFOobbyPpdbbfuTvF6n69yjtlnly9Xl6uOQHoHwb6Npt9Y6rd3FnatQvn6PG48RU6FCapuNP1MvCU8dOpOENBsLrWNdhVtLV21rQpztqX6129NqKTmm8S2vGXy7vBwfD/ABHqNlGdLT7mrQjUk6k6dONKW+aik2t0W29sei8jPb8S6rTuLi7p3U43VdbK9ZO331Y0orkk1hpRS+SgOj+FXh+0taOl3FjbwowuoVI15285ytpVVtcVCM/WT5T54WV7emP4L9Lta9rrte6s4ahOxoUKtvRnvy5YuG4x28+eyK6djltc1q/v9kr64q3KppeH4jiox3p4xGOFl7euOx96XrN/pUqqtK87WVdR8XwvCqKfhymlltNcm5r7QO14h4Zso1eGrmnaysFqt3b0rvTaspzSg61NSa3c1HDw+S+XHknnO38Kmj6fYW9RWdnYwqxr0Y7oOu6sI/Ke9Nbdrwovn89Hn97qd/cXVvcV7ipXu4uE7arKpCbpuE90XFfJglKOeiXLmbOqcU6rfUKlK7u6la3co+JTq+BTUpwaklyim2mk8L2AejfolpU1R1pUKcdGWmzr1bNN/wDeLkoYz15yWP2oLzNbgDQdPuNF9Lu7WynXnd1oOVfxo04xzlQjsy8LovYebx1W99EjYKtU9DqyU423qbJSdTKecZXrrOM9eZuaRxJqljbKNnc1re2zOaUI0XHduSk/Wi3nLQHSaHoVtdWvFdT0WDq2m70CEFUk6LzW2qmnhterHGV5Gr8G3DtG4qanVvrarcy021Velp7U6U7ipJTaTj8p/ISS771yZ+LQ4l1SzqVq1O6q0at9tq15xVGTrPGYyknFpcpPpjqY567qSuf7QdxXjdOMY+lLZFyg00otJbZL1OjXzVkDquKNFtKmnaTqNOy/sqtdXsbatZZn4dSlunicYySa5U12XKb68mdZxvwlpNta6i52trZRo2++xuKdxJV6l1tlin4PdblFYzzy+nU8q1vVNRvK8ZX1xOtWoJyg6k6UIUknzaUcQi8pdueEa2rXF3e1KlzeTdetDFKpVqeHGS28tuIpefZAeq6Bw7pi0XTbitaWVSvXoylUlcuupVJJvpsT5mh8GXDdre6TVr1LC3u7n090lG4qyobKOyk5Lcs81uk0sc2cPYcaara0adG3va1KjSW2nTjGi4xj5LMWzTt9fvKVJ0qdxUp0XXjdOEdi/vMZRkqmcZzmMX17Ab3wgadaWeq3dCwbdvSlFbdzmqdXat9NSfNpP7Oa7HPG3qWoVrutOtc1HWr1Mb6kowjKWEks7Uk3hJZ9hqgAUAQFAEBSAQFAEBQBpgAAAAAAAFIUAUFAFIUD7pVHCSlF4lFpxfkz6p1pRjtTWPW6xi2tyxLDaysrk8GMoGSVeTiot+qsY5RzyzjLxl43PGfMtevOrLdUk5y585c3jLf4tmIoGWFeaaak04xcItcmovOUn26v7T69KqZn62XNtybjFvLTTayuTaby11MJQMquJrw+azSw4PbHKw8rnjL5vuI15qDgpNQa2uPLDW7d+JiKBkq1pT27mntSivVinhJJZwufJLqJVpOO1tuOEscuizj/AOn9p8ADYd5U3upu21GmnKCjB83l9F19p8+kT2yjlbZycpLbH5T6tcuXuMQAFAAAoAhQUCAoA+QUAQFIBAUAaQAAAAAAAKECgCoAClIUAUFAFIUCgFAFAAFBQABQAKAAKAICgCApVFvpz+rmB8goAhCgCEKANEAAAAACBQCKgAKUhQKAioAUIIClIUCgFAFAAoBUAKQoAoKBCgoENinXiopOnCWOrecvmYABsu5j2pU1z9r5Z9v2H3aXcYSm0vD3ZxKO54W1rbyaffKw+sVnK6aYA2J3MXGqlCKc36ksLME1iXveF9XPCWTYqX9JzUlRjGOzbtiocpbk0+afTt59+XI/PIBuxvaahRj4STgpKco43SThKLf/ALZ9yMNe4jKlSgo4lDOZcua/r+ma7AEAAH//2Q==" alt="" />
              </div>
              <div class="title">
                <h3>Build A Password Generator with React JS - Beginners Tutorial</h3>
                <a href="">FutureCoders</a>
                <span>10M Views • 3 Months Ago</span>
              </div>
            </div>
          </div>
          <!-- Single Video Ends -->

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://img.youtube.com/vi/46cXFUzR9XM/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img
                  src="data:image/jpeg;base64,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"
                  alt=""
                />
              </div>
              <div class="title">
                <h3>Bella Ciao Full Song | La Casa De Papel | Money Heist | Netflix India</h3>
                <a href="">Netflix</a>
                <span>10M Views • 11 Months Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://img.youtube.com/vi/d2na6sCyM5Q/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img
                  src="data:image/jpeg;base64,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"
                  alt=""
                />
              </div>
              <div class="title">
                <h3>DON'T EVER GIVE UP - Elon Musk (Motivational Video)</h3>
                <a href=""> Chispa Motivation</a>
                <span>10M Views • 1 Month Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://img.youtube.com/vi/2Ji-clqUYnA/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img
                  src="https://yt3.ggpht.com/ytc/AAUvwniaHN7MZyFEiNvdHuKMzIWnDF604Z2--O4GCMq-FA=s48-c-k-c0x00ffffff-no-rj"
                  alt=""
                />
              </div>
              <div class="title">
                <h3>Javascript Fundamentals</h3>
                <a href="">Coding Addict</a>
                <span>179K • 8 Months Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://img.youtube.com/vi/3PHXvlpOkf4/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img
                  src="https://yt3.ggpht.com/ytc/AAUvwnifaQZvAunS0OFb2y_cieoVjLCVjqQW8Exf3BC1gg=s48-c-k-c0x00ffffff-no-rj"
                  alt=""
                />
              </div>
              <div class="title">
                <h3>Build 15 JavaScript Projects - Vanilla JavaScript Course</h3>
                <a href=""> freeCodeCamp.org </a>
                <span>470K Views • 8 Months Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://img.youtube.com/vi/CVClHLwv-4I/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img
                  src="https://yt3.ggpht.com/ytc/AAUvwnhIz_0Su6HhW6Ym50QCroJCAnF10X9xnnMDboN2=s48-c-k-c0x00ffffff-no-rj"
                  alt=""
                />
              </div>
              <div class="title">
                <h3>Build Real Time Face Detection With JavaScript</h3>
                <a href=""> Web Dev Simplified </a>
                <span>875K Views • 1 Year Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="data:image/jpeg;base64,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" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img
                  src="data:image/jpeg;base64,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"
                  alt=""
                />
              </div>
              <div class="title">
                <h3>AWS Basics for Beginners - Full Course</h3>
                <a href=""> freeCodeCamp.org </a>
                <span>36K Views • 1 Day Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://img.youtube.com/vi/PpXUTUXU7Qc/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img src="http://aninex.com/images/srvc/web_de_icon.png" alt="" />
              </div>
              <div class="title">
                <h3>
                  Top 5 Programming Languages to Learn in 2021 | Best Programming Languages to Learn
                </h3>
                <a href="">FutureCoders</a>
                <span>10M Views • 3 Months Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://img.youtube.com/vi/YpTmcCBBdTE/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img src="http://aninex.com/images/srvc/web_de_icon.png" alt="" />
              </div>
              <div class="title">
                <h3>Build A Password Generator with React JS - Beginners Tutorial</h3>
                <a href="">FutureCoders</a>
                <span>10M Views • 3 Months Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://img.youtube.com/vi/46cXFUzR9XM/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img
                  src="https://yt3.ggpht.com/ytc/AAUvwnh53ZRIGnyzC28QrfuggCINb3cfNbNWo4Uc6qR9=s48-c-k-c0x00ffffff-no-rj"
                  alt=""
                />
              </div>
              <div class="title">
                <h3>Bella Ciao Full Song | La Casa De Papel | Money Heist | Netflix India</h3>
                <a href="">Netflix</a>
                <span>10M Views • 11 Months Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://img.youtube.com/vi/d2na6sCyM5Q/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img
                  src="https://yt3.ggpht.com/ytc/AAUvwnhESPVEatju_1yE-03-KLeSrnSLc5yy0RcvhPd5Lg=s48-c-k-c0x00ffffff-no-rj"
                  alt=""
                />
              </div>
              <div class="title">
                <h3>DON'T EVER GIVE UP - Elon Musk (Motivational Video)</h3>
                <a href=""> Chispa Motivation</a>
                <span>10M Views • 1 Month Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://img.youtube.com/vi/2Ji-clqUYnA/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img
                  src="https://yt3.ggpht.com/ytc/AAUvwniaHN7MZyFEiNvdHuKMzIWnDF604Z2--O4GCMq-FA=s48-c-k-c0x00ffffff-no-rj"
                  alt=""
                />
              </div>
              <div class="title">
                <h3>Javascript Fundamentals</h3>
                <a href="">Coding Addict</a>
                <span>179K • 8 Months Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://img.youtube.com/vi/3PHXvlpOkf4/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img
                  src="https://yt3.ggpht.com/ytc/AAUvwnifaQZvAunS0OFb2y_cieoVjLCVjqQW8Exf3BC1gg=s48-c-k-c0x00ffffff-no-rj"
                  alt=""
                />
              </div>
              <div class="title">
                <h3>Build 15 JavaScript Projects - Vanilla JavaScript Course</h3>
                <a href=""> freeCodeCamp.org </a>
                <span>470K Views • 8 Months Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://img.youtube.com/vi/CVClHLwv-4I/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img
                  src="https://yt3.ggpht.com/ytc/AAUvwnhIz_0Su6HhW6Ym50QCroJCAnF10X9xnnMDboN2=s48-c-k-c0x00ffffff-no-rj"
                  alt=""
                />
              </div>
              <div class="title">
                <h3>Build Real Time Face Detection With JavaScript</h3>
                <a href=""> Web Dev Simplified </a>
                <span>875K Views • 1 Year Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://img.youtube.com/vi/ulprqHHWlng/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img
                  src="https://yt3.ggpht.com/ytc/AAUvwnifaQZvAunS0OFb2y_cieoVjLCVjqQW8Exf3BC1gg=s48-c-k-c0x00ffffff-no-rj"
                  alt=""
                />
              </div>
              <div class="title">
                <h3>AWS Basics for Beginners - Full Course</h3>
                <a href=""> freeCodeCamp.org </a>
                <span>36K Views • 1 Day Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://img.youtube.com/vi/PpXUTUXU7Qc/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img src="http://aninex.com/images/srvc/web_de_icon.png" alt="" />
              </div>
              <div class="title">
                <h3>
                  Top 5 Programming Languages to Learn in 2021 | Best Programming Languages to Learn
                </h3>
                <a href="">FutureCoders</a>
                <span>10M Views • 3 Months Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://img.youtube.com/vi/YpTmcCBBdTE/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img src="http://aninex.com/images/srvc/web_de_icon.png" alt="" />
              </div>
              <div class="title">
                <h3>Build A Password Generator with React JS - Beginners Tutorial</h3>
                <a href="">FutureCoders</a>
                <span>10M Views • 3 Months Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://img.youtube.com/vi/46cXFUzR9XM/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img
                  src="https://yt3.ggpht.com/ytc/AAUvwnh53ZRIGnyzC28QrfuggCINb3cfNbNWo4Uc6qR9=s48-c-k-c0x00ffffff-no-rj"
                  alt=""
                />
              </div>
              <div class="title">
                <h3>Bella Ciao Full Song | La Casa De Papel | Money Heist | Netflix India</h3>
                <a href="">Netflix</a>
                <span>10M Views • 11 Months Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://img.youtube.com/vi/d2na6sCyM5Q/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img
                  src="https://yt3.ggpht.com/ytc/AAUvwnhESPVEatju_1yE-03-KLeSrnSLc5yy0RcvhPd5Lg=s48-c-k-c0x00ffffff-no-rj"
                  alt=""
                />
              </div>
              <div class="title">
                <h3>DON'T EVER GIVE UP - Elon Musk (Motivational Video)</h3>
                <a href=""> Chispa Motivation</a>
                <span>10M Views • 1 Month Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://i.ytimg.com/vi/PV1dSFYvkHk/mqdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img
                  src="https://i.ytimg.com/vi/W6NZfCO5SIk/maxresdefault.jpg"
                  alt=""
                />
              </div>
              <div class="title">
                <h3>Javascript Fundamentals</h3>
                <a href="">Coding Addict</a>
                <span>800M • 8 Months Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/20200214165928/Web-Development-Course-Thumbnail.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img
                  src="https://i.ytimg.com/vi/RkAXDGnz0FQ/maxresdefault.jpg"
                  alt=""
                />
              </div>
              <div class="title">
                <h3>Web development Course</h3>
                <a href=""> Web development Course </a>
                <span>470K Views • 8 hours Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://i.ytimg.com/vi/h_Dj_gVXao4/maxresdefault.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img
                  src="https://ai.thestempedia.com/wp-content/uploads/2022/07/Expression-Recognizer_YT-Thumbnail.jpg"
                  alt=""
                />
              </div>
              <div class="title">
                <h3>Build Real Time Face Detection With JavaScript</h3>
                <a href=""> Web Dev Simplified </a>
                <span>875K Views • 1 day Ago</span>
              </div>
            </div>
          </div>

          <div class="video">
            <div class="video__thumbnail">
              <img src="https://marketplace.canva.com/EAFAMirCsX4/2/0/1600w/canva-purple-creative-livestream-youtube-thumbnail-X2eVuOzURSM.jpg" alt="" />
            </div>
            <div class="video__details">
              <div class="author">
                <img
                  src="https://www.techsmith.com/blog/wp-content/uploads/2021/02/TSC-thumbnail-example-1024x576.png"alt=""
                />
              </div>
              <div class="title">
                <h3>AWS Basics for Beginners - Full Course</h3>
                <a href=""> freeCodeCamp.org </a>
                <span>36K Views • 2 hours Ago</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <script src="index.js"></script>
    <!-- Main Body Ends -->
  </body>
</html>
