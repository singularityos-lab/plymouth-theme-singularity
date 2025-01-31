singularity_bgrt_plymouth = i18n.merge_file(
  input: configure_file(
    input: 'singularity-bgrt.plymouth.desktop',
    output: 'singularity-bgrt.plymouth.desktop',
    configuration: {
      'PLYMOUTH_THEME_PATH': plymouth_theme_path,
    },
  ),
  output: 'singularity-bgrt.plymouth',
  type: 'desktop',
  po_dir: po_dir,
  install: true,
  install_dir: plymouth_theme_path / 'singularity-bgrt',
)

install_subdir('bgrt_assets',
  install_dir:plymouth_theme_path / 'singularity-bgrt',
  strip_directory: true,)
