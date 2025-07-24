# Laracasts: Rapid Laravel Apps With Filament

## Lessons

### Section 1: Blueprint

1. **Create Models with Blueprint**
    - Create a Laravel project and install the Blueprint package to quickly scaffold Models and Controllers

### Section 2: Filament Forms

1. **Introduction to Filament**
    - Install Filament package and build the resources to quickly scaffold an admin user interface
2. **Basic Form Inputs**
    - Starts off by enabling hot reloading on Livewire and Filament changes
3. **Select Input**
    - Touched on creating Enums (fixed, distinct values): `app/Enums/Region.php`
    - Made the Conference region's select input _live_ so that when you select a region, the venue drop down then populates with only venues in that region
    - Converted the venue drop down into a _searchable_ combo box with `preload`, as well as creating new venue and editing existing venue capabilities