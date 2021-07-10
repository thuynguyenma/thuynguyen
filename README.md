# Thuy T.P. Nguyen, PhD

![Portray](portray.jpeg)

* Showcase your research interests, publications, your curriculum vitae, the people in your research group, and your contact information.

* Manage courses that you are teaching.

* Provide updates to your students and faulty.

## Installation

### Ruby Gem Method

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "academic-jekyll-theme"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: academic-jekyll-theme
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install academic-jekyll-theme

## Usage

### Layouts

The following sections describe usage instructions for this Jekyll theme,including available layouts, includes, sass and/or assets.

#### Publications

The `_layouts/publications.html` layout can be used to showcase selected publications, or the entire catalogue of publications. Direct links to the paper can be used, or a PDF copy of the paper can be served. Publications are defined in the `_data/publications.yml` file, and any PDF files that are served can be placed in the `publications` directory.

#### Courses

The `_layouts/courses.html` layout can be used to showcase courses that were taught in the past or are currently being taught. Courses are defined in the `_data/settings.yml` file, and markdown pages for each course with the `_layouts/page.html` layout can be placed in the `courses` directory. Related course material, such as PDF files, can also be placed in the `courses` directory in a subdirectory with the same name as the corresponding course.

#### CV

The `_layouts/cv.html` layout can be used to showcase a curriculum vitae. The sections of the cv are defined in the `_data/cv` directory, where each section has its own `<section>.yml` file.

#### Contact

The `_layouts/contact.html` layout can be used to provide contact information for the research group or the people that lead the research group. Contact information is defined in the `_data/settings.yml` file.

