singularity_logo_plymouth = configure_file(
  input: 'singularity-logo.plymouth.in',
  output: '@BASENAME@',
  configuration: {
    'PLYMOUTH_THEME_PATH': plymouth_theme_path,
  },
  install: true,
  install_dir: plymouth_theme_path / 'singularity-logo',
)

singularity_logo_scale2_plymouth = configure_file(
  input: 'singularity-logo-scale-2.plymouth.in',
  output: '@BASENAME@',
  configuration: {
    'PLYMOUTH_THEME_PATH': plymouth_theme_path,
  },
  install: true,
  install_dir: plymouth_theme_path / 'singularity-logo',
)

install_subdir('logo_assets',
  install_dir:plymouth_theme_path / 'singularity-logo',
  strip_directory: true,)
