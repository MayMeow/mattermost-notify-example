# mattermost-notify-example

```yaml
- uses: MayMeow/action-mattermost-notify@main
        with:
          url: ${{ secrets.MATTERMOST_WEBHOOK }}
          message: "Hello world from ${{ github.repository }}"
```
