<template>
  <div class="document-preview">
    <h6 class="color-yv-blue"> E-commerce</h6>
    <div class="document-preview__image"></div>
    <h5 class="color-yv-red">
      Mobile payment fraud is rising, how can trends merchants prevent it?
    </h5>
    <p>
      Mobile payment fraud is rising every year. Learn the significant
      m-commerce fraud trends and what merchants can do to prevent payment fraud
      happening to their customers.
    </p>
    <a class="link link--to_right link--green">
      <span class="link-text">Find out more</span>
      <svg class="link-icon" viewBox="0 0 19 11" width="100%" height="100%">
        <path d="M18.797 5.063l-5.063 5.062V5.93H0V4.195h13.734V0z"></path>
      </svg>
    </a>
  </div>
</template>

<style scoped lang="postcss">

.document-preview {
  --document-preview-margin-bottom: 30px;
}

@media screen and (min-width: 1024px) {
  .document-preview {
    --document-preview-margin-bottom: 50px;
  }
}

.document-preview {
  margin-top: 0;
  margin-right: var(--gap-xl);
  margin-left: var(--gap-xl);
  margin-bottom: var(--document-preview-margin-bottom);
}

.document-preview__image {
  width: 100%;
  margin-bottom: var(--gap-xxl);
  height: 0;
  padding-top: 55%;

  /* temp */
  background-color: var(--color-light-cream);
}

</style>
