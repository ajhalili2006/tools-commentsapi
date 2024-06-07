# comments.andreijiroh.xyz / comments.lorebooks.wiki

_[Open upstream README for translations and more up-to-date details](https://giscus.app)_

This is a [giscus] instance used as a service for @recaptime-dev and friends, maintained under @ajhalili2006's Vercel account and powered by [GitHub Discussions][discussions].

You can monitor deployments at <https://github.com/ajhalili2006/tools-commentsapi> and we'll try our best to keep in sync with upstream (other than minimal changes, like this README).

## How it works

When giscus loads, the [GitHub Discussions search API][search-api] is used to find the Discussion associated with the page based on a chosen mapping (URL, `pathname`, `<title>`, etc.). If a matching discussion cannot be found, the giscus bot will automatically create a discussion the first time someone leaves a comment or reaction.

To comment, visitors must authorize the [giscus app][giscus-app] to [post on their behalf][authorization] using the GitHub OAuth flow. Alternatively, visitors can comment on the GitHub Discussion directly. You can moderate the comments on GitHub.

If you're using giscus, consider [starring 🌟 the upstream repo on GitHub][repo] and adding the [`giscus`][giscus-topic] topic [to your repository][topic-howto]! 🎉

<!-- configuration -->

## Advanced usage

You can add additional configurations (e.g. allowing specific origins) by following the [advanced usage guide][advanced-usage].

To use giscus with React, Vue, or Svelte, check out the [giscus component library][giscus-component].

## Migrating

If you've previously used other systems that utilize GitHub Issues (e.g. [utterances][utterances], [gitalk][gitalk]), you can [convert the existing issues into discussions][convert]. After the conversion, just make sure that the mapping between the discussion titles and the pages are correct, then giscus will automatically use the discussions.

## Contributing

See [CONTRIBUTING.md][contributing] (please contribute to upstream instead)

[giscus-component]: https://github.com/giscus/giscus-component
[repo]: https://github.com/giscus/giscus
[giscus-topic]: https://github.com/topics/giscus
[topic-howto]: https://docs.github.com/en/github/administering-a-repository/classifying-your-repository-with-topics
[advanced-usage]: https://github.com/giscus/giscus/blob/main/ADVANCED-USAGE.md
[utterances]: https://github.com/utterance/utterances
[gitalk]: https://github.com/gitalk/gitalk
[convert]: https://docs.github.com/en/discussions/managing-discussions-for-your-community/moderating-discussions#converting-an-issue-to-a-discussion
[contributing]: https://github.com/giscus/giscus/blob/main/CONTRIBUTING.md
[giscus]: https://giscus.app
[discussions]: https://docs.github.com/en/discussions
[repo]: https://github.com/giscus/giscus
[advanced-usage]: https://github.com/giscus/giscus/blob/main/ADVANCED-USAGE.md
[search-api]: https://docs.github.com/en/graphql/guides/using-the-graphql-api-for-discussions#search
[giscus-app]: https://github.com/apps/giscus
[authorization]: https://docs.github.com/en/developers/apps/identifying-and-authorizing-users-for-github-apps

<!-- end -->
---

[![Powered by Vercel](public/powered-by-vercel.svg)][vercel]

[vercel]: https://vercel.com/?utm_source=giscus&utm_campaign=oss
