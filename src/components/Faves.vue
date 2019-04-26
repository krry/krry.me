<template>
  <div class="faves">
    <h2>New Favorites</h2>
    <ol class="lovelist">
      <li>
        <a href="./iching">The I Ching</a>
      </li>
      <li>
        <a
          href="https://www.nonviolentcommunication.com/aboutnvc/aboutnvc.htm"
          target="_blank"
          rel="noopener"
          >Non-Violent Communication</a>
        &amp;
        <a href="https://www.goodreads.com/book/show/235625.Conscious_Loving"
           >Conscious Loving</a>
      </li>
      <li>
        That mystical hylozoic nexus where existence is musical and beauty is value.
      </li>
      <li>Sustainability in all its forms</li>
      <li>Following intuition to solution</li>
      <li>0th principles: starting from scratch</li>
      <li><a href="https://reddit.com/r/onebag">#onebag</a> life</li>
      <li>The Cosmogony of <a href="https://www.himalayanacademy.com/media/books/12-beliefs-of-saivism_ei/web/ch06a.html">Saivism</a></li>
    </ol>
  </div>
</template>

<script>
export default {
  name: 'Faves',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.lovelist h2 {
  text-align: left;
}

ol.lovelist {
  margin-top: 0;
  padding-top: 0;
  list-style: decimal url(data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7);
}

.lovelist li {
  margin-bottom: 0.25em;
  position: relative;
  font-family: Aleo, serif;
  font-weight: lighter;
}

.lovelist li::before {
  position: absolute;
  left: -1.25em;
  font-size: 1.25em;
  font-weight: normal;
}

.lovelist li:nth-child(8n-1)::before {
  content: "\2661";
}

.lovelist li:nth-child(8n)::before {
  content: "\2665";
}

.lovelist li:nth-child(8n-4)::before {
  content: "\2764";
}

.lovelist li:nth-child(8n-5)::before {
  content: "\2763";
  left: -1.1em;
}

.lovelist li:nth-child(8n-6)::before {
  content: "\2765";
  left: -1.125em;
}

.lovelist li:nth-child(8n-3)::before {
  content: "\2766";
}

.lovelist li:nth-child(8n-2)::before {
  content: "\2767";
  left: -1.125em;
  bottom: -0.075em;
  font-size: 110%;
}

.lovelist li:nth-child(8n-7)::before {
  content: "\2619";
  left: -1.125em;
  bottom: -0.075em;
  font-size: 120%;
}
</style>
