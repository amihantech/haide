<template>
  <main class="container">
    <div class="content">
      <h1 class="title">Haide</h1>
      <p>Coming soon.</p>
    </div>
    <footer>© 2026 Amihan Technologies</footer>
  </main>
</template>

<script>
export default {
  head() {
    return {
      title: 'Haide.io',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Haide is coming soon.',
        },
      ],
    }
  },
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.content {
  margin: auto;
  text-align: center;
}

.title {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 600;
  font-size: 4rem;
  color: #35495e;
  letter-spacing: 0.05em;
}

p {
  color: #64748b;
  font-size: 1.125rem;
}

footer {
  padding: 1.5rem;
  color: #94a3b8;
  font-size: 0.875rem;
  text-align: center;
}
</style>
