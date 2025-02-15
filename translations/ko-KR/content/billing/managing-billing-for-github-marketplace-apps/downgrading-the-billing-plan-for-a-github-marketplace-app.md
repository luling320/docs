---
title: Downgrading the billing plan for a GitHub Marketplace app
intro: 'If you''d like to use a different billing plan, you can downgrade your {% data variables.product.prodname_marketplace %} app at any time.'
redirect_from:
  - /github/setting-up-and-managing-billing-and-payments-on-github/downgrading-the-billing-plan-for-a-github-marketplace-app
  - /articles/downgrading-an-app-for-your-personal-account/
  - /articles/downgrading-an-app-for-your-organization/
  - /articles/downgrading-the-billing-plan-for-a-github-marketplace-app
  - /github/setting-up-and-managing-billing-and-payments-on-github/managing-billing-for-github-marketplace-apps/downgrading-the-billing-plan-for-a-github-marketplace-app
versions:
  fpt: '*'
  ghec: '*'
type: how_to
topics:
  - Downgrades
  - Marketplace
  - Organizations
  - User account
shortTitle: Downgrade billing plan
---

When you downgrade an app, your subscription remains active until the end of your current billing cycle. The downgrade takes effect on your next billing date. For more information, see "[About billing for {% data variables.product.prodname_marketplace %}](/articles/about-billing-for-github-marketplace)."

{% data reusables.marketplace.downgrade-marketplace-only %}

## Downgrading an app for your personal account

{% data reusables.user_settings.access_settings %}
{% data reusables.user_settings.billing_plans %}
{% data reusables.marketplace.downgrade-app-billing-settings %}
{% data reusables.marketplace.choose-new-plan %}
{% data reusables.marketplace.choose-new-quantity %}
{% data reusables.marketplace.issue-plan-changes %}

## Downgrading an app for your organization

{% data reusables.marketplace.marketplace-org-perms %}

{% data reusables.profile.access_org %}
{% data reusables.profile.org_settings %}
{% data reusables.organizations.billing_plans %}
{% data reusables.marketplace.downgrade-app-billing-settings %}
{% data reusables.marketplace.choose-new-plan %}
{% data reusables.marketplace.choose-new-quantity %}
{% data reusables.marketplace.issue-plan-changes %}

## 더 읽을거리

- "[Canceling a {% data variables.product.prodname_marketplace %} app](/articles/canceling-a-github-marketplace-app/)"
