```dart
  final job = jobs.first;
  assert(job is (String,String), 'what`s the job title and tech?');
  final whoami = switch(job) {
      ('dev','java/kotlin') => '$job = 8 years',
      ('dev','swift') => '$job = 6 years',
      ('dev','dart') => '$job = 5 years',
      ('arc','java/kotlin') => '$job = 5 years',
      ('arc','swift') => '$job = 4 years',
      ('arc','dart') => '$job = 3 years',
      ('lead','java/kotlin') => '$job = 4 years',
      ('lead','swift') => '$job = 3 years',        
      ('lead','dart') => '$job = 1 years',
      _ => 'learning'
    };
  print(whoami);
```
