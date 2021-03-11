# GCP Subnet Usage

This tool calculates availability of IP addresses in existing subnets.

## Problem statement

This action is currently [pretty difficult](https://stackoverflow.com/questions/39967432/list-instances-in-subnetwork/40269419). Ideally, we'd wrap GCloud SDK to calculate and display current subnet usage.

Someone recommended [steampipe](https://hub.steampipe.io/plugins/turbot/gcp/tables/gcp_compute_address) so maybe that's a good thing to use for this.
