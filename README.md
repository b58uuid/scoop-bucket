# B58UUID Scoop Bucket

Official Scoop bucket for [B58UUID CLI](https://github.com/b58uuid/b58uuid-cli).

## Installation

```powershell
# Add bucket
scoop bucket add b58uuid https://github.com/b58uuid/scoop-bucket

# Install
scoop install b58uuid
```

## Usage

```powershell
# Encode UUID to B58UUID
b58uuid encode 550e8400-e29b-41d4-a716-446655440000

# Decode B58UUID to UUID
b58uuid decode BWBeN28Vb7cMEx7Ym8AUzs

# Generate random B58UUID
b58uuid generate

# Validate format
b58uuid validate BWBeN28Vb7cMEx7Ym8AUzs

# Get help
b58uuid --help
```

## Updating

```powershell
scoop update
scoop update b58uuid
```

## Uninstalling

```powershell
scoop uninstall b58uuid
scoop bucket rm b58uuid
```

## Links

- **Website**: https://b58uuid.io
- **GitHub**: https://github.com/b58uuid/b58uuid-cli
- **Documentation**: https://github.com/b58uuid/b58uuid-cli#readme

## License

MIT License - see [LICENSE](https://github.com/b58uuid/b58uuid-cli/blob/main/LICENSE)
