generate:
    rm -f talosconfig worker.yaml controlplane.yaml
    talosctl gen config talos "https://talos.home.lab:6443" --config-patch-control-plane @controlplane.patch.yaml
