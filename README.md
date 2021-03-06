# `django-tutorials-py-app`

Hello SMART-on-FHIR Django py webapp

[![verification](https://github.com/percebus/django-tutorials-py-app/actions/workflows/always.yml/badge.svg)](https://github.com/percebus/django-tutorials-py-app/actions/workflows/always.yml) [![Dependency Review](https://github.com/percebus/django-tutorials-py-app/actions/workflows/pull_request.yml/badge.svg)](https://github.com/percebus/django-tutorials-py-app/actions/workflows/pull_request.yml)

## History

See [HISTORY.md](./HISTORY.md)

## `webapp/`

See [`webapp/README.md`](./webapp/README.md)

## Setup

### Environment Variables

#### `env/{environment}.ba.sh`

See [`env/README.md`](./env/README.md)

#### `.env`

Set same variables as your default `env/{environment}.ba.sh`.

i.e. `env/localhost.ba.sh`

### First time

#### `venv`

```bash
$> python -m venv venv
$> source venv/Scripts/activate
```

#### `setup(:ci)`

```bash
$> npm run setup
```

Not working: Need to make `source` work from `npm`

### Dependencies

[![Dependency Review](https://github.com/percebus/django-tutorials-py-app/actions/workflows/pull_request.yml/badge.svg)](https://github.com/percebus/django-tutorials-py-app/actions/workflows/pull_request.yml)

```bash
$> npm install
```

## Development

[![verification](https://github.com/percebus/django-tutorials-py-app/actions/workflows/always.yml/badge.svg)](https://github.com/percebus/django-tutorials-py-app/actions/workflows/always.yml)

### Run

#### local

```bash
$> npm start
```

#### Docker

```bash
$> npm run start:docker
```

### Browser

```bash
$> npm run browser
```

## Resources

### Django

- [Writing your first Django app, part 1](https://docs.djangoproject.com/en/4.0/intro/tutorial01)

### SMART/FHIR

- [FHIR, SMART, CSD Hooks overview](https://www.youtube.com/watch?v=z5FnHpSxMvs&ab_channel=JoshMandel)
- [SMART FHIR Python Client](http://docs.smarthealthit.org/client-py/)
