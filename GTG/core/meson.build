gtg_core_sources = [
  '__init__.py',
  'borg.py',
  'cleanxml.py',
  'clipboard.py',
  'config.py',
  'datastore.py',
  'dates.py',
  'dirs.py',
  'firstrun_tasks.py',
  'info.py',
  'interruptible.py',
  'keyring.py',
  'logger.py',
  'networkmanager.py',
  'requester.py',
  'search.py',
  'tag.py',
  'task.py',
  'taskxml.py',
  'timer.py',
  'translations.py',
  'treefactory.py',
  'twokeydict.py',
  'urlregex.py',
  'watchdog.py',
]

gtg_core_plugin_sources = [
  'plugins/__init__.py',
  'plugins/api.py',
  'plugins/engine.py',
]

python3.install_sources(gtg_core_sources, subdir: 'GTG' / 'core')
python3.install_sources(gtg_core_plugin_sources, subdir: 'GTG' / 'core' / 'plugins')
