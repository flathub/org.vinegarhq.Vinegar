# org.vinegarhq.Vinegar

```sh
# Generate go.mod.yml from vinegar source
go run github.com/dennwc/flatpak-go-mod@latest ../vinegar

flatpak install --user org.freedesktop.Sdk.Extension.golang org.gnome.Sdk
flatpak-builder --install --user --force-clean repo/ org.vinegarhq.Vinegar.yml
```
