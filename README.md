# Discourse Filtered Topics Lists

Allows creating custom topic list using filters. The lists then can be displayed in selected plugin outlet for selected pages.

Inspired from [Discourse Featured Lists](https://github.com/nolosb/discourse-featured-lists)

## Recommended

Enable the [`experimental topics filter`](/admin/site_settings/category/all_results?filter=experimental_topics_filter)
setting, and install the complementary UI component to help with creating,
and testing your queries.

<https://github.com/discourse/discourse-experimental-filter-component>

## Available CSS classes

```scss
.filtered-topics-list {
    &__wrapper {
    }

    &__header {
        h2 {
        }
    }

    &__content {
    }
}

.filtered-topics-list {
    &.below-site-header,
    &.above-main-container,
    &.before-topic-list,
    &.after-topic-list,
    &.topic-list-bottom,
    &.main-outlet-bottom,
    &.before-main-outlet {

        &__wrapper {
        }

        &__header {
            h2 {
            }
        }

        &__content {
        }
    }
}
```
