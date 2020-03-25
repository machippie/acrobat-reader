
## Default Variables

### acrobat_reader_started

Start in background after install

#### Default value

```yaml
acrobat_reader_started: true
```

### acrobat_reader_user

User to run user-specific commands

#### Default value

```yaml
acrobat_reader_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
