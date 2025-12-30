# Python concept index
- ```query
    {:title "All Python concepts"
     :query [:find (pull ?b [*])
             :where
             [?b :block/properties ?p]
             [(get ?p :tags) ?tags]
             [(clojure.string/includes? (or ?tags "") "python")]
             ]
     :result-transform (fn [result] result)
     :breadcrumb-show? false}
  ```
- public:: true