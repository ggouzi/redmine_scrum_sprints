# Redmine_scrum_sprints
Redmine plugin to adapt scrum methods in order to help managing your projects.

This plugin was made by Emilio González Montaña.

Original link https://www.redmine.org/plugins/scrum-plugin

No change was made.




## This plugin allows to follow Scrum methodology with Redmine:

    Sprint task board with drag & drop.
    Sprint burndown chart.
    Product backlog with drag & drop.
    Product backlog burndown chart.
    Release planning.
    Edit PBIs & tasks with a pop-up directly in PB or Sprint board.
    Easy to setup, plugin settings & configuration per project.
    Several new permissions in Administration section.

	
## Installation notes

Download from Files section in the plugin page.

As any Redmine plugin, just deploy it in the plugins folder, rename folder to scrum and then run:

`bundle exec rake redmine:plugins:migrate RAILS_ENV=production`

Set-up plugin settings (in Admin view), then create Sprint & PB in each needed project settings.

Select a project and clic on "Configuration" → "Modules", then enable scrum plugin. You'll see two new tabs "Backlogs and "Sprint".