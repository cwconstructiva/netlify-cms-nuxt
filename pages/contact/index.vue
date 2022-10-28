<template>
  <main>
    <section class="w-full max-w-5xl mx-auto">
      <h1 class="title">Contact</h1>
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sequi, dignissimos necessitatibus consequatur quos
        laborum sint at, perspiciatis voluptatem ad delectus quo! Eligendi soluta quo earum voluptas ducimus praesentium
        sapiente eaque!
      </p>
      </section>
      <section>
      
        <form name="contact" method="POST" data-netlify="true">
          <p>
            <label>Your Name: <input type="text" name="name" /></label>
          </p>
          <p>
            <label>Your Email: <input type="email" name="email" /></label>
          </p>
          <p>
            <label>Your Role: <select name="role[]" multiple>
                <option value="leader">Leader</option>
                <option value="follower">Follower</option>
              </select></label>
          </p>
          <p>
            <label>Message: <textarea name="message"></textarea></label>
          </p>
          <p>
            <button type="submit">Send</button>
          </p>
        </form>

    </section>
  </main>
</template>
