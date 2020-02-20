# PHP Base Image (WIP)

This Repo contains the build instructions for the PHP base image (Stretch and Buster). All PHP images should inherit from this image.

## Documentation

This image is automatically build with following cron expression `0 0 * * *`.

### Environment vars

| Argument                              | Default Value                                             | Description |
| :---                                  | :---                                                      | :---         |

## Contributing

## Changelog

All notable changes to this project will be documented in this section.

### 2020-02-20

- added source prepare script to get php src by version argument
- removed duplicate if statement in docker-entrypoint
- updated MozJPEG to 1d2320994dd0d293d39cfaea3d13060b60f32c45
- updated Tiff to 4.1.0
- updated WebP to 1.1.0
- updated OpenJPEG to 563ecfb55ca77c0fc5ea19e4885e00f55ec82ca9
- updated ImageMagick to 7.0.9-24

### 2020-02-18

- added workflow to trigger dockerhub autobuild