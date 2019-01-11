## Changelog

#### 1.1.2
* **Fix**: Fix wrong label in block details [issue #9](https://github.com/front/cloud-blocks/issues/9)
* **Add**: Polish translation. (Thanks to [ajotka](https://github.com/front/cloud-blocks/pull/8))
* **Add**: Update counter & label in menu. (Thanks to [ajotka](https://github.com/front/cloud-blocks/pull/10))


#### 1.1.1
* **Fix**: Update blocks if new version available on the cloud
* **Enhancement**: Improvement in local block screenshots. The filename can be both screenshot or thumbnail and it could be in blocks root directory or build folder

#### 1.1.0
* **Fix**: Change array dereferencing in activation hook
* **Fix**: Show block in installed list even after block removed from Gutenberg Cloud
* **Fix**: Don't display Installed notice on blocks in Installed tab
* **Fix**: Search blocks in installed and local blocks
* **Add**: Listing for local custom blocks, install and delete them. (In previous versions, blocks were activated automatically, from now on, you need to explicitly activate/deactivate them in the `Local` tab.)
* **Add**: Default block screenshot
* **Change**: Change minimum required php version
* **Change**: Check for db structure update in upgrader_process_complete hook instead of init

#### 1.0.10
* **Fix**: Fix block js dependency introduced in Gutenberg 4.5.1

#### 1.0.9
* **Change**: Change increase and decrease number of installations of a block

#### 1.0.8
* **Fix**: Fix some issues in previous version release

#### 1.0.7
* **Change:** Private custom blocks now should be under **wp-content/uploads/gutenberg-blocks/**.
* **Add:** Implement UI to upload zip file with custom block [issue #3](https://github.com/front/cloud-blocks/issues/3)
* **Fix:** Fix a bug about enqueue custom blocks assets [issue #4](https://github.com/front/cloud-blocks/issues/4)
* **Fix:** Fix an issue with javascript if search query is empty

#### 1.0.6
* **Add:** Implement order for blocks (Latest or Popular)
* **Fix:** Block counter in popular and latest tabls
* **Fix:** Display block author
* **Change**: Blocks homepage url 
* **Change:** If there is no installed blocks, redirect to Popular tab instead of Installed
* **Change:** Update documentations

#### 1.0.5
* **Add**: Add modal with block info (like themes) [issue #2](https://github.com/front/cloud-blocks/issues/2)
* **Fix**: Limit enqueue of block styles only to editor or front-end

#### 1.0.4
* **Fix**: Fix translations variable name in javascript files
* **Change**: Update readme

#### 1.0.3
* **Change**: Update readme
* **Add**: More docs

#### 1.0.2
* **Change**: Some translation fixes
* **Change**: Better documentation and screenshot
* **Added**: Italian translation. (Thanks to [cipo28](https://github.com/front/cloud-blocks/pull/1))

#### 1.0.1
* **Fix**: is_plugin_active() undefined fix
* **Fix**: Change strings functions to static

#### 1.0.0
* Initial plugin