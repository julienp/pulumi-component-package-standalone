# Components as Buildable Python Packages

This component is structured as a buildable Python package with a `pyproject.toml` file. The `PulumiPlugin.yaml` file serves as a marker for Pulumi to recognize the package as a component. By "exporting" the components in `__init__.py`, we obviate the need to call `component_provider_host`.
