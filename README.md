## About 

Filament test

## Notes

- Make new models. ie. php artisan make:model Location -m
- Edit the migration. database > migrations.
- Run the migration. php artisan migrate
- Add relationships on Model. ie. BelongsTo, HasOne, HasMany, etc.
- Add resource for the model. php artisan make:filament-resource Location
- Add a form to your resource. ie. Edit LocationResource.php and add components to the form function.
  If you would like to automatically make the form and table instead use "php artisan make:filament-resource Customer --generate"
  If you would like to add functionality to restore, force delete, and filter trashed records, use --soft-deletes flag when making resource.
  By default, only List, Create and Edit pages are generated for your resource. If you'd also like a View page, use the --view flag.
- I already unguarded all models on AppServiceProvider (Filament has its own protections.)
