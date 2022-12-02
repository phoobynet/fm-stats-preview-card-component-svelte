<div class="card">
  <div class="card__content">
    <h1>Get <em>insights</em> that help your business grow.</h1>
    <p>Discover the benefits of data analytics and make better decisions regarding revenue, customer experience, and
      overall efficiency.</p>
    <ul class="card__stats">
      <li>
        <div>10k+</div>
        <div>companies</div>
      </li>
      <li>
        <div>314</div>
        <div>templates</div>
      </li>
      <li>
        <div>12M+</div>
        <div>queries</div>
      </li>
    </ul>
  </div>
  <div class="card__heading">
    <img
      alt=""
    >
  </div>
</div>

<style>
  .card {
    border-radius: 0.5rem;
    overflow: hidden;
    display: grid;
    grid-template-rows: 15rem auto;
    background-color: #1B1937;
    width: 20.438rem;
    height: 48.75rem;
  }

  .card__content {
    grid-column-start: 1;
    grid-row-start: 2;
    margin: 2.5rem 2rem 0 2rem;
  }

  .card__content h1 {
    text-align: center;
    font-weight: bold;
    font-size: 1.75rem;
    line-height: 2rem;
    letter-spacing: 0;
  }

  .card__content h1 > em {
    color: var(--soft-violet);
    font-style: normal;
  }

  .card__content p {
    text-align: center;
    line-height: 25px;
    letter-spacing: 0;
    opacity: .75;
    margin: 1.5rem 0 0 0;
  }

  .card__heading {
    background-color: var(--soft-violet);
  }

  .card__heading img {
    opacity: .75;
    mix-blend-mode: multiply;
    content: url("@/assets/images/image-header-mobile.jpg");
    width: 327px;
    height: 240px;
  }

  .card__stats {
    padding: 0;
    list-style: none;
    display: flex;
    flex-direction: column;
    align-items: center;
    row-gap: 1rem;
  }

  .card__stats li {
    text-align: center;
  }

  .card__stats li > div:first-child {
    font-size: 24px;
    font-weight: 700;
    letter-spacing: 0;
  }

  .card__stats li > div:last-child {
    font-family: 'Lexend Deca';
    opacity: 0.60;
    font-size: 12px;
    line-height: 25px;
    font-weight: 400;
    letter-spacing: 1px;
    text-transform: uppercase;
  }

  @media screen and (min-width: 1440px) {
    .card {
      grid-template-columns: auto 33.75rem;
      grid-template-rows: auto;
      width: 69.375rem;
      height: 27.875rem;
      margin-bottom: 0;
    }

    .card__content {
      grid-column-start: 1;
      grid-row-start: 1;
      margin: 4.5rem 4.5rem 0;
    }

    .card__content h1 {
      text-align: left;
      font-size: 2.25rem;
      line-height: 2.75rem;
    }

    .card__heading img {
      content: url("@/assets/images/image-header-desktop.jpg");
      width: 540px;
      height: 446px;
    }

    .card__content p {
      text-align: left;
      margin: 1.5rem 0 0 0;
    }

    .card__stats {
      flex-direction: row;
      column-gap: 1rem;
    }

    .card__stats li {
      text-align: left;
    }
  }
</style>
