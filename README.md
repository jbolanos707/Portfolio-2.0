# Portfolio-2.0

<a href="APP LINK IF APPLICABLE" target="#"><APP LINK NAME></a>

By Jennifer Bolanos (<a href=https://github.com/jbolanos707/Portfolio-2.0.git target="#">GitHub</a>)

@ Epicodus Programming School, Portland, OR

GNU General Public License, version 3 (see below). Copyright (c) 2015 Jennifer Bolanos.

### Description

Portfolio - 2.0

A 4-week project dedicated to creating a personal portfolio site to showcase
student work.

####Week 1:

-Creates, edits, and deletes skills and projects

*week 1 can be found at https://github.com/jbolanos707/Portfolio-On-Rails.git

*was unable to continue to work on this repo due to not being able to have the gem Devise function with it.

####Week 2: (current project)
-Creates a blog with authorization and authentication features

### Author(s)

Jennifer Bolanos

### Setup

This app was written in `ruby '2.2.0'` and `rails '4.2.3'`

Clone this repo with
```console
> git clone https://github.com/jbolanos707/Portfolio-2.0.git
```

Install gems:

```console
> bundle install
```

Create database
```console
> rake db:create
> rake db:migrate
> rake db:test:prepare
```

Start App:
```console
> rails server
```
Navigate in your browser to localhost:3000

As a "guest" you can view and navigate the site but will not be able to manipulate posts or delete comments. 
To test these functions visit localhost:3000/users/sign_up. Once signed in you will have all admin access.

### License ###
Copyright  (C)  2015  Jennifer Bolanos

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
