Drupal development envrionment

1. run composer
2. copy settings.local.php to sites/default
3. uncomment sites/default/setting.php if (file_exists(...
4. add to settings.local.php
  $class_loader->addPsr4('Drupal\\webprofiler\\', [ __DIR__ . '/../../modules/devel/webprofiler/src']);
  $settings['container_base_class'] = \Drupal\webprofiler\DependencyInjection\TraceableContainer::class;

