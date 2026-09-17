# QR Call Staff

A tiny QR-based request system for restaurants, hotels, clinics, offices and service venues where a customer needs to call staff without searching for someone or installing an app.

## Problem

Guests wave at waiters, call reception, walk to a counter, or repeatedly ask for simple service. Staff also do not have a clear prioritized queue of requests.

## Product

Each table, room, seat or service point has a QR code. The guest scans it and taps a request:

```text
Call waiter
Bring bill
Water
Clean table/room
Need assistance
Other request
```

The request appears instantly on a staff dashboard or staff phone.

## Target customers

- cafes/restaurants
- hotels/guest houses
- clinics/waiting areas
- coworking/offices
- lounges
- entertainment venues
- car washes/service waiting areas

## MVP

- business/location account
- zones/tables/rooms/service points
- unique QR per point
- no-login guest request page
- configurable request buttons
- request queue dashboard
- New / Accepted / Done statuses
- sound/push/Telegram notification for staff
- response-time measurement
- basic analytics
- abuse/rate limiting

## Pricing hypothesis

| Plan | Indicative price |
|---|---:|
| Pilot | free / 49,000 UZS month |
| Basic | 99,000 UZS/location/month |
| Pro | 199,000 UZS/location/month |
| Hotel/large venue | 399,000+ UZS/location/month |

Optional printed QR setup/branding: **100,000-500,000 UZS** depending on number of service points.

## Why a business may pay

- faster staff response
- fewer guests trying to find employees
- simple measurable service times
- better staff accountability
- no customer app installation
- extremely low technical/operating cost

## Later features

- waiter assignment
- hotel room-service requests
- multilingual guest UI
- escalation if request is ignored
- customer satisfaction after completion
- QR Restaurant Pay integration
- staff workload analytics

## Success metrics

- median response time
- requests completed
- ignored/escalated requests
- staff/customer satisfaction
- repeat use

## Shared-core fit

This is one of the simplest verticals of the shared platform: `ServicePoint`, `RequestType`, `ServiceRequest`, `Assignee`, and `Completion`.
