<!-- <script>
import postgres from "postgres";

let { PGHOST, PGDATABASE, PGUSER, PGPASSWORD } = process.env;
const conn = postgres({
  host: PGHOST,
  database: PGDATABASE,
  username: PGUSER,
  password: PGPASSWORD,
  port: 5432,
  ssl: "require",
});

function selectAll() {
  return conn.query("SELECT * FROM hello_world");
} 
</script> -->

<header>
  <h1>My feeds</h1>
  <nav>
    <a href="/feeds">Feeds</a>
    <a href="/about">About</a>
    <a href="dashboard">Profile</a>

  </nav>
</header>
<section>
  <main>
    <section class="grid">

    </section>
  </main>
  <aside>
    <h2>filter by</h2>
  </aside>
</section>
