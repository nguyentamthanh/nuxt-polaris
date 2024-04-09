<template>
  <!-- <div style="width: 200px">
    <Button
      fullWidth
      textAlign="left"
      :disclosure="expanded ? 'up' : 'down'"
      @click="onClick"
    >
      {{ expanded ? "Show less" : "Show more" }}
    </Button>
  </div> -->
  <div style="height: 500px">
    <div
      class="Polaris-Frame Polaris-Frame--hasNav Polaris-Frame--hasTopBar"
      data-polaris-layer="true"
      data-has-navigation="true"
    >
      <div class="Polaris-Frame__Skip">
        <a href="#AppFrameMain">
          <span
            class="Polaris-Text--root Polaris-Text--bodyLg Polaris-Text--medium"
            >Skip to content</span
          >
        </a>
      </div>
      <div
        class="Polaris-Frame__TopBar"
        data-polaris-layer="true"
        data-polaris-top-bar="true"
        id="AppFrameTopBar"
      >
        <div class="Polaris-TopBar">
          <div class="Polaris-TopBar__Container">
            <div class="Polaris-TopBar__LeftContent">
              <button
                type="button"
                class="Polaris-TopBar__NavigationIcon"
                aria-label="Toggle menu"
              >
                <div class="Polaris-TopBar__IconWrapper">
                  <span class="Polaris-Icon">
                    <svg
                      viewBox="0 0 20 20"
                      class="Polaris-Icon__Svg"
                      focusable="false"
                      aria-hidden="true"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M3 4.75a.75.75 0 0 1 .75-.75h12.5a.75.75 0 0 1 0 1.5h-12.5a.75.75 0 0 1-.75-.75Z"
                      ></path>
                      <path
                        fill-rule="evenodd"
                        d="M3 10a.75.75 0 0 1 .75-.75h12.5a.75.75 0 0 1 0 1.5h-12.5a.75.75 0 0 1-.75-.75Z"
                      ></path>
                      <path
                        fill-rule="evenodd"
                        d="M3 15.25a.75.75 0 0 1 .75-.75h12.5a.75.75 0 0 1 0 1.5h-12.5a.75.75 0 0 1-.75-.75Z"
                      ></path>
                    </svg>
                  </span>
                </div>
              </button>
              <div
                class="Polaris-TopBar__LogoContainer Polaris-TopBar__LogoDisplayControl"
              >
                <a
                  class="Polaris-TopBar__LogoLink"
                  style="width: 86px"
                  href=""
                  data-polaris-unstyled="true"
                >
                  <img
                    alt="Shopify"
                    src="https://cdn.shopify.com/s/files/1/2376/3301/files/Shopify_Secondary_Inverted.png"
                    class="Polaris-TopBar__Logo"
                    style="width: 86px"
                  />
                </a>
              </div>
            </div>
            <div class="Polaris-TopBar__Search">
              <div class="Polaris-TopBar-SearchField">
                <span class="Polaris-Text--root Polaris-Text--visuallyHidden">
                  <label for=":R32cq6:">Search</label>
                </span>
                <input
                  id=":R32cq6:"
                  class="Polaris-TopBar-SearchField__Input"
                  placeholder="Search"
                  type="search"
                  autocapitalize="off"
                  autocomplete="off"
                  autocorrect="off"
                  value=""
                />
                <span class="Polaris-TopBar-SearchField__Icon">
                  <span class="Polaris-Icon">
                    <svg
                      viewBox="0 0 20 20"
                      class="Polaris-Icon__Svg"
                      focusable="false"
                      aria-hidden="true"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M12.323 13.383a5.5 5.5 0 1 1 1.06-1.06l2.897 2.897a.75.75 0 1 1-1.06 1.06l-2.897-2.897Zm.677-4.383a4 4 0 1 1-8 0 4 4 0 0 1 8 0Z"
                      ></path>
                    </svg>
                  </span>
                </span>
                <div class="Polaris-TopBar-SearchField__Backdrop"></div>
              </div>
              <div class="Polaris-TopBar-Search">
                <div class="Polaris-TopBar-Search__SearchContent">
                  <div class="Polaris-TopBar-Search__Results">
                    <div class="Polaris-Box">
                      <div
                        class="Polaris-Box"
                        style="
                          --pc-box-padding-block-start-xs: var(--p-space-150);
                          --pc-box-padding-block-end-xs: var(--p-space-150);
                          --pc-box-padding-inline-start-xs: var(--p-space-150);
                          --pc-box-padding-inline-end-xs: var(--p-space-150);
                        "
                        tabindex="-1"
                      >
                        <ul
                          class="Polaris-BlockStack Polaris-BlockStack--listReset"
                          style="
                            --pc-block-stack-order: column;
                            --pc-block-stack-gap-xs: var(--p-space-050);
                          "
                        >
                          <li class="Polaris-Box">
                            <div
                              class="Polaris-InlineStack"
                              style="
                                --pc-inline-stack-wrap: nowrap;
                                --pc-inline-stack-flex-direction-xs: row;
                              "
                            >
                              <button
                                type="button"
                                class="Polaris-ActionList__Item Polaris-ActionList--default"
                              >
                                <div
                                  class="Polaris-Box"
                                  style="--pc-box-width: 100%"
                                >
                                  <div
                                    class="Polaris-InlineStack"
                                    style="
                                      --pc-inline-stack-block-align: center;
                                      --pc-inline-stack-wrap: nowrap;
                                      --pc-inline-stack-gap-xs: var(
                                        --p-space-150
                                      );
                                      --pc-inline-stack-flex-direction-xs: row;
                                    "
                                  >
                                    <span class="Polaris-ActionList__Text">
                                      <span
                                        class="Polaris-Text--root Polaris-Text--bodyMd Polaris-Text--regular"
                                      >
                                        <span
                                          class="Polaris-Text--root Polaris-Text--bodyMd Polaris-Text--regular"
                                          >Shopify help center</span
                                        >
                                      </span>
                                    </span>
                                  </div>
                                </div>
                              </button>
                            </div>
                          </li>
                          <li class="Polaris-Box">
                            <div
                              class="Polaris-InlineStack"
                              style="
                                --pc-inline-stack-wrap: nowrap;
                                --pc-inline-stack-flex-direction-xs: row;
                              "
                            >
                              <button
                                type="button"
                                class="Polaris-ActionList__Item Polaris-ActionList--default"
                              >
                                <div
                                  class="Polaris-Box"
                                  style="--pc-box-width: 100%"
                                >
                                  <div
                                    class="Polaris-InlineStack"
                                    style="
                                      --pc-inline-stack-block-align: center;
                                      --pc-inline-stack-wrap: nowrap;
                                      --pc-inline-stack-gap-xs: var(
                                        --p-space-150
                                      );
                                      --pc-inline-stack-flex-direction-xs: row;
                                    "
                                  >
                                    <span class="Polaris-ActionList__Text">
                                      <span
                                        class="Polaris-Text--root Polaris-Text--bodyMd Polaris-Text--regular"
                                      >
                                        <span
                                          class="Polaris-Text--root Polaris-Text--bodyMd Polaris-Text--regular"
                                          >Community forums</span
                                        >
                                      </span>
                                    </span>
                                  </div>
                                </div>
                              </button>
                            </div>
                          </li>
                        </ul>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="Polaris-TopBar__RightContent">
              <div class="Polaris-TopBar__SecondaryMenu"></div>
              <div>
                <div class="Polaris-TopBar-Menu__ActivatorWrapper">
                  <button
                    type="button"
                    class="Polaris-TopBar-Menu__Activator Polaris-TopBar-Menu__Activator--userMenu"
                    tabindex="0"
                    aria-controls=":R5icq6:"
                    aria-owns=":R5icq6:"
                    aria-expanded="false"
                    data-state="closed"
                  >
                    <span class="Polaris-TopBar-UserMenu__Details">
                      <p
                        class="Polaris-Text--root Polaris-Text--bodySm Polaris-Text--medium Polaris-Text--block Polaris-Text--start Polaris-Text--truncate"
                      >
                        Dharma
                      </p>
                      <span>
                        <p
                          class="Polaris-Text--root Polaris-Text--bodyXs Polaris-Text--block Polaris-Text--start Polaris-Text--textInverseSecondary Polaris-Text--truncate"
                        >
                          Jaded Pixel
                        </p>
                      </span>
                    </span>
                    <div
                      class="Polaris-MessageIndicator__MessageIndicatorWrapper"
                    >
                      <span
                        aria-label="Dharma"
                        role="img"
                        class="Polaris-Avatar Polaris-Avatar--sizeMd Polaris-Avatar--styleThree"
                      >
                        <span class="Polaris-Avatar__Initials">
                          <svg class="Polaris-Avatar__Svg" viewBox="0 0 40 40">
                            <text
                              class="Polaris-Avatar__Text"
                              x="50%"
                              y="50%"
                              dy="0.35em"
                              fill="currentColor"
                              text-anchor="middle"
                            >
                              D
                            </text>
                          </svg>
                        </span>
                      </span>
                    </div>
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div>
        <div
          aria-label="Navigation"
          class="Polaris-Frame__Navigation"
          id="AppFrameNav"
        >
          <nav class="Polaris-Navigation">
            <div class="Polaris-Navigation__LogoContainer">
              <a
                class="Polaris-Navigation__LogoLink"
                style="width: 86px"
                href=""
                data-polaris-unstyled="true"
              >
                <img
                  alt="Shopify"
                  src="https://cdn.shopify.com/s/files/1/2376/3301/files/Shopify_Secondary_Inverted.png"
                  class="Polaris-Navigation__Logo"
                  style="width: 86px"
                />
              </a>
            </div>
            <div
              class="Polaris-Navigation__PrimaryNavigation Polaris-Scrollable Polaris-Scrollable--vertical Polaris-Scrollable--horizontal Polaris-Scrollable--scrollbarWidthThin"
              data-polaris-scrollable="true"
            >
              <ul class="Polaris-Navigation__Section">
                <li class="Polaris-Navigation__ListItem">
                  <div class="Polaris-Navigation__ItemWrapper">
                    <div class="Polaris-Navigation__ItemInnerWrapper">
                      <button type="button" class="Polaris-Navigation__Item">
                        <div class="Polaris-Navigation__Icon">
                          <span class="Polaris-Icon">
                            <svg
                              viewBox="0 0 20 20"
                              class="Polaris-Icon__Svg"
                              focusable="false"
                              aria-hidden="true"
                            >
                              <path
                                fill-rule="evenodd"
                                d="M16.5 10a.75.75 0 0 1-.75.75h-9.69l2.72 2.72a.75.75 0 0 1-1.06 1.06l-4-4a.75.75 0 0 1 0-1.06l4-4a.75.75 0 1 1 1.06 1.06l-2.72 2.72h9.69a.75.75 0 0 1 .75.75Z"
                              ></path>
                            </svg>
                          </span>
                        </div>
                        <span class="Polaris-Navigation__Text">
                          <span
                            class="Polaris-Text--root Polaris-Text--bodyMd Polaris-Text--medium"
                            >Back to Shopify</span
                          >
                        </span>
                      </button>
                    </div>
                  </div>
                </li>
              </ul>
              <ul
                class="Polaris-Navigation__Section Polaris-Navigation__Section--withSeparator"
              >
                <li class="Polaris-Navigation__SectionHeading">
                  <span
                    class="Polaris-Text--root Polaris-Text--bodySm Polaris-Text--medium Polaris-Text--subdued"
                    >Jaded Pixel App</span
                  >
                  <button
                    type="button"
                    class="Polaris-Navigation__Action"
                    aria-label="Contact support"
                  >
                    <span class="Polaris-Icon">
                      <svg
                        viewBox="0 0 20 20"
                        class="Polaris-Icon__Svg"
                        focusable="false"
                        aria-hidden="true"
                      >
                        <path
                          fill-rule="evenodd"
                          d="M7 15v-2.291a3 3 0 0 1-2.5-2.959v-1.25a3 3 0 0 1 3-3h5a3 3 0 0 1 3 3v1.25a3 3 0 0 1-3 3h-2.461l-3.039 2.25Zm3.534-.75h1.966a4.5 4.5 0 0 0 4.5-4.5v-1.25a4.5 4.5 0 0 0-4.5-4.5h-5a4.5 4.5 0 0 0-4.5 4.5v1.25a4.498 4.498 0 0 0 2.5 4.032v1.218a1.5 1.5 0 0 0 2.393 1.206l2.64-1.956Zm-4.534-6.5a.75.75 0 0 1 .75-.75h5.5a.75.75 0 0 1 0 1.5h-5.5a.75.75 0 0 1-.75-.75Zm.75 2a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5h-3.5Z"
                        ></path>
                      </svg>
                    </span>
                  </button>
                </li>
                <li class="Polaris-Navigation__ListItem">
                  <div class="Polaris-Navigation__ItemWrapper">
                    <div class="Polaris-Navigation__ItemInnerWrapper">
                      <button type="button" class="Polaris-Navigation__Item">
                        <div class="Polaris-Navigation__Icon">
                          <span class="Polaris-Icon">
                            <svg
                              viewBox="0 0 20 20"
                              class="Polaris-Icon__Svg"
                              focusable="false"
                              aria-hidden="true"
                            >
                              <path
                                fill-rule="evenodd"
                                d="M8.344 3.692a2.25 2.25 0 0 1 3.312 0l3.854 4.19a3.75 3.75 0 0 1 .99 2.538v3.33a2.75 2.75 0 0 1-2.75 2.75h-1.75a1.5 1.5 0 0 1-1.5-1.5v-2h-1v2a1.5 1.5 0 0 1-1.5 1.5h-1.75a2.75 2.75 0 0 1-2.75-2.75v-3.33c0-.94.353-1.847.99-2.539l3.854-4.189Zm2.208 1.016a.75.75 0 0 0-1.104 0l-3.854 4.189a2.25 2.25 0 0 0-.594 1.523v3.33c0 .69.56 1.25 1.25 1.25h1.75v-2a1.5 1.5 0 0 1 1.5-1.5h1a1.5 1.5 0 0 1 1.5 1.5v2h1.75c.69 0 1.25-.56 1.25-1.25v-3.33a2.25 2.25 0 0 0-.594-1.523l-3.854-4.19Z"
                              ></path>
                            </svg>
                          </span>
                        </div>
                        <span class="Polaris-Navigation__Text">
                          <span
                            class="Polaris-Text--root Polaris-Text--bodyMd Polaris-Text--medium"
                            >Dashboard</span
                          >
                        </span>
                      </button>
                    </div>
                  </div>
                </li>
                <li class="Polaris-Navigation__ListItem">
                  <div class="Polaris-Navigation__ItemWrapper">
                    <div class="Polaris-Navigation__ItemInnerWrapper">
                      <button type="button" class="Polaris-Navigation__Item">
                        <div class="Polaris-Navigation__Icon">
                          <span class="Polaris-Icon">
                            <svg
                              viewBox="0 0 20 20"
                              class="Polaris-Icon__Svg"
                              focusable="false"
                              aria-hidden="true"
                            >
                              <path
                                fill-rule="evenodd"
                                d="M6.976 3.5a2.75 2.75 0 0 0-2.72 2.347l-.662 4.46a8.75 8.75 0 0 0-.094 1.282v1.661a3.25 3.25 0 0 0 3.25 3.25h6.5a3.25 3.25 0 0 0 3.25-3.25v-1.66c0-.43-.032-.858-.095-1.283l-.66-4.46a2.75 2.75 0 0 0-2.72-2.347h-6.05Zm-1.237 2.567a1.25 1.25 0 0 1 1.237-1.067h6.048c.62 0 1.146.454 1.237 1.067l.583 3.933h-2.484a1.25 1.25 0 0 0-1.185.855l-.159.474a.25.25 0 0 1-.237.171h-1.558a.25.25 0 0 1-.237-.17l-.159-.475a1.25 1.25 0 0 0-1.185-.855h-2.484l.583-3.933Zm-.738 5.433-.001.09v1.66c0 .966.784 1.75 1.75 1.75h6.5a1.75 1.75 0 0 0 1.75-1.75v-1.75h-2.46l-.1.303a1.75 1.75 0 0 1-1.66 1.197h-1.56a1.75 1.75 0 0 1-1.66-1.197l-.1-.303h-2.46Z"
                              ></path>
                            </svg>
                          </span>
                        </div>
                        <span class="Polaris-Navigation__Text">
                          <span
                            class="Polaris-Text--root Polaris-Text--bodyMd Polaris-Text--medium"
                            >Jaded Pixel Orders</span
                          >
                        </span>
                      </button>
                    </div>
                  </div>
                </li>
              </ul>
            </div>
          </nav>
          <button
            type="button"
            class="Polaris-Frame__NavigationDismiss"
            aria-hidden="true"
            aria-label="Close navigation"
            tabindex="-1"
          >
            <span class="Polaris-Icon">
              <svg
                viewBox="0 0 20 20"
                class="Polaris-Icon__Svg"
                focusable="false"
                aria-hidden="true"
              >
                <path
                  d="M12.72 13.78a.75.75 0 1 0 1.06-1.06l-2.72-2.72 2.72-2.72a.75.75 0 0 0-1.06-1.06l-2.72 2.72-2.72-2.72a.75.75 0 0 0-1.06 1.06l2.72 2.72-2.72 2.72a.75.75 0 1 0 1.06 1.06l2.72-2.72 2.72 2.72Z"
                ></path>
              </svg>
            </span>
          </button>
        </div>
      </div>
      <div
        class="Polaris-Frame__ContextualSaveBar Polaris-Frame-CSSAnimation--startFade"
      ></div>
      <main
        class="Polaris-Frame__Main"
        id="AppFrameMain"
        data-has-global-ribbon="false"
      >
        <div class="Polaris-Frame__Content">
          <div class="Polaris-Page">
            <div
              class="Polaris-Box"
              style="
                --pc-box-padding-block-start-xs: var(--p-space-400);
                --pc-box-padding-block-start-md: var(--p-space-600);
                --pc-box-padding-block-end-xs: var(--p-space-400);
                --pc-box-padding-block-end-md: var(--p-space-600);
                --pc-box-padding-inline-start-xs: var(--p-space-400);
                --pc-box-padding-inline-start-sm: var(--p-space-0);
                --pc-box-padding-inline-end-xs: var(--p-space-400);
                --pc-box-padding-inline-end-sm: var(--p-space-0);
                position: relative;
              "
            >
              <div role="status">
                <p class="Polaris-Text--root Polaris-Text--visuallyHidden"></p>
              </div>
              <div
                class="Polaris-Page-Header--isSingleRow Polaris-Page-Header--noBreadcrumbs Polaris-Page-Header--mediumTitle"
              >
                <div class="Polaris-Page-Header__Row">
                  <div
                    class="Polaris-Page-Header__TitleWrapper Polaris-Page-Header__TitleWrapperExpand"
                  >
                    <div class="Polaris-Header-Title__TitleWrapper">
                      <h1 class="Polaris-Header-Title">
                        <span
                          class="Polaris-Text--root Polaris-Text--headingLg Polaris-Text--bold"
                          >Account</span
                        >
                      </h1>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="">
              <div class="Polaris-Layout">
                <a id="SkipToContentTarget" tabindex="-1"> </a>
                <div class="Polaris-Layout__AnnotatedSection">
                  <div class="Polaris-Layout__AnnotationWrapper">
                    <div class="Polaris-Layout__Annotation">
                      <div
                        class="Polaris-TextContainer Polaris-TextContainer--spacingTight"
                      >
                        <h2 class="Polaris-Text--root Polaris-Text--headingMd">
                          Account details
                        </h2>
                        <div
                          class="Polaris-Box"
                          style="--pc-box-color: var(--p-color-text-secondary)"
                        >
                          <p class="Polaris-Text--root Polaris-Text--bodyMd">
                            Jaded Pixel will use this as your account
                            information.
                          </p>
                        </div>
                      </div>
                    </div>
                    <div class="Polaris-Layout__AnnotationContent">
                      <div class="Polaris-LegacyCard">
                        <div
                          class="Polaris-LegacyCard__Section Polaris-LegacyCard__FirstSectionPadding Polaris-LegacyCard__LastSectionPadding"
                        >
                          <div
                            class="Polaris-BlockStack"
                            style="
                              --pc-block-stack-order: column;
                              --pc-block-stack-gap-xs: var(--p-space-400);
                            "
                          >
                            <div
                              class="Polaris-FormLayout__Item Polaris-FormLayout--grouped"
                            >
                              <div class="">
                                <div class="Polaris-Labelled__LabelWrapper">
                                  <div class="Polaris-Label">
                                    <label
                                      id=":R6l9ncq6:Label"
                                      for=":R6l9ncq6:"
                                      class="Polaris-Label__Text"
                                    >
                                      <span
                                        class="Polaris-Text--root Polaris-Text--bodyMd"
                                        >Full name</span
                                      >
                                    </label>
                                  </div>
                                </div>
                                <div class="Polaris-Connected">
                                  <div
                                    class="Polaris-Connected__Item Polaris-Connected__Item--primary"
                                  >
                                    <div
                                      class="Polaris-TextField Polaris-TextField--hasValue"
                                    >
                                      <input
                                        id=":R6l9ncq6:"
                                        autocomplete="name"
                                        class="Polaris-TextField__Input"
                                        type="text"
                                        aria-labelledby=":R6l9ncq6:Label"
                                        aria-invalid="false"
                                        value="Jaded Pixel"
                                      />
                                      <div
                                        class="Polaris-TextField__Backdrop"
                                      ></div>
                                    </div>
                                  </div>
                                </div>
                              </div>
                            </div>
                            <div
                              class="Polaris-FormLayout__Item Polaris-FormLayout--grouped"
                            >
                              <div class="">
                                <div class="Polaris-Labelled__LabelWrapper">
                                  <div class="Polaris-Label">
                                    <label
                                      id=":Ral9ncq6:Label"
                                      for=":Ral9ncq6:"
                                      class="Polaris-Label__Text"
                                    >
                                      <span
                                        class="Polaris-Text--root Polaris-Text--bodyMd"
                                        >Email</span
                                      >
                                    </label>
                                  </div>
                                </div>
                                <div class="Polaris-Connected">
                                  <div
                                    class="Polaris-Connected__Item Polaris-Connected__Item--primary"
                                  >
                                    <div
                                      class="Polaris-TextField Polaris-TextField--hasValue"
                                    >
                                      <input
                                        id=":Ral9ncq6:"
                                        autocomplete="email"
                                        class="Polaris-TextField__Input"
                                        type="email"
                                        aria-labelledby=":Ral9ncq6:Label"
                                        aria-invalid="false"
                                        value="dharma@jadedpixel.com"
                                      />
                                      <div
                                        class="Polaris-TextField__Backdrop"
                                      ></div>
                                    </div>
                                  </div>
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </main>
    </div>
    <div id="PolarisPortalsContainer">
      <div
        data-portal-id="popover-:r0:"
        class="p-theme-light Polaris-ThemeProvider--themeContainer"
      ></div>
      <div
        data-portal-id="modal-:Rmncq6:"
        class="p-theme-light Polaris-ThemeProvider--themeContainer"
      >
        <div></div>
      </div>
      <div
        data-portal-id="toast-:R8cq6:"
        class="p-theme-light Polaris-ThemeProvider--themeContainer"
      >
        <div class="Polaris-Frame-ToastManager" aria-live="assertive"></div>
      </div>
    </div>
  </div>
  <div
    data-portal-id="popover-:r0:"
    class="p-theme-light Polaris-ThemeProvider--themeContainer"
  ></div>
  <div
    data-portal-id="modal-:Rmncq6:"
    class="p-theme-light Polaris-ThemeProvider--themeContainer"
  >
    <div></div>
  </div>
  <div
    data-portal-id="toast-:R8cq6:"
    class="p-theme-light Polaris-ThemeProvider--themeContainer"
  >
    <div class="Polaris-Frame-ToastManager" aria-live="assertive"></div>
  </div>
</template>

<script setup>
const expanded = ref(false);
const onClick = () => {
  expanded.value = !expanded.value;
};
</script>
