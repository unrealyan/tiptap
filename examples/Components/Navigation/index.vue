<template>
  <div class="navigation">

    <h1 class="navigation__logo">
      tiptap
    </h1>

    <div>
      <a class="navigation__link" href="https://github.com/scrumpy/tiptap/blob/master/CONTRIBUTING.md" target="_blank">
        Contribute
      </a>
      <a class="navigation__github-link" href="https://github.com/scrumpy/tiptap" target="_blank">
        <icon class="navigation__icon" name="github" />
      </a>
    </div>

  </div>
</template>

<script>
import Icon from 'Components/Icon'

export default {
  components: {
    Icon,
  },
}
</script>

<style lang="scss" src="./style.scss" scoped></style>
