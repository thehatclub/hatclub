<nav
  class="navbar bg-dark fixed-top navbar-dark p-3 mb-5 border-bottom"
  aria-label="First navbar example"
>
  <div class="container-fluid">
    <a class="navbar-brand" href="#home"
      ><img
        src="/logo.png"
        alt="The Hat Club"
        class="fav img-fluid"
        width="30"
      /> The Hat Club</a
    >
    <button
      class="navbar-toggler collapsed"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#navbarsExample01"
      aria-controls="navbarsExample01"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon" />
    </button>

    <div class="navbar-collapse collapse" id="navbarsExample01" style="">
      <ul class="navbar-nav me-auto mb-2">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#home">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#apps">Apps</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#about">About</a>
        </li>
      </ul>
      <form class="d-flex" role="search">
        <input
          class="form-control me-2"
          type="search"
          placeholder="Search Blog..."
          aria-label="Search"
        />
        <button class="btn btn-warning fw-bold" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>
