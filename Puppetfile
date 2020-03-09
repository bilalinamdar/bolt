# frozen_string_literal: true

forge "http://forge.puppetlabs.com"

moduledir File.join(File.dirname(__FILE__), 'modules')

# Core modules used by 'apply'
mod 'puppetlabs-service', '1.2.0'
mod 'puppetlabs-puppet_agent', '3.0.2'
mod 'puppetlabs-facts', '1.0.0'

# Core types and providers for Puppet 6
mod 'puppetlabs-augeas_core', '1.0.5'
mod 'puppetlabs-host_core', '1.0.3'
mod 'puppetlabs-scheduled_task', '2.0.1'
mod 'puppetlabs-sshkeys_core', '1.0.3'
mod 'puppetlabs-zfs_core', '1.0.4'
mod 'puppetlabs-cron_core', '1.0.3'
mod 'puppetlabs-mount_core', '1.0.4'
mod 'puppetlabs-selinux_core', '1.0.4'
mod 'puppetlabs-yumrepo_core', '1.0.6'
mod 'puppetlabs-zone_core', '1.0.3'

# Useful additional modules
mod 'puppetlabs-package', '1.1.0'
mod 'puppetlabs-puppet_conf', '0.6.0'
mod 'puppetlabs-python_task_helper', '0.3.0'
mod 'puppetlabs-reboot', '3.0.0'
mod 'puppetlabs-ruby_task_helper', '0.4.0'
mod 'puppetlabs-ruby_plugin_helper', '0.1.0'

# Plugin modules
mod 'puppetlabs-azure_inventory', '0.3.0'
mod 'puppetlabs-terraform', '0.4.0'
mod 'puppetlabs-vault', '0.3.0'
mod 'puppetlabs-aws_inventory', '0.4.0'
mod 'puppetlabs-yaml', '0.2.0'

# If we don't list these modules explicitly, r10k will purge them
mod 'canary', local: true
mod 'aggregate', local: true
mod 'puppetdb_fact', local: true
