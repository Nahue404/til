# Blueprints

Split routes into blueprints per feature (`auth`, `admin`, `songs`) and register them in the factory with `app.register_blueprint(bp, url_prefix="/admin")`.
