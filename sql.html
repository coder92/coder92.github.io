-- uzi_pdd.account definition

CREATE TABLE `account` (
  `key` varchar(50) NOT NULL,
  `title` varchar(50) NOT NULL,
  `kafka_partition_id` int NOT NULL DEFAULT '0',
  `is_active` tinyint(1) NOT NULL DEFAULT '1',
  PRIMARY KEY (`key`),
  UNIQUE KEY `title` (`title`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;


-- uzi_pdd.account_group definition

CREATE TABLE `account_group` (
  `id` int NOT NULL AUTO_INCREMENT,
  `key` varchar(255) NOT NULL,
  `name` varchar(255) NOT NULL,
  `is_active` tinyint(1) NOT NULL,
  `created_by` varchar(50) NOT NULL,
  `created_at` datetime NOT NULL,
  `updated_by` varchar(50) NOT NULL,
  `updated_at` datetime NOT NULL,
  PRIMARY KEY (`id`),
  UNIQUE KEY `key` (`key`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;


-- uzi_pdd.account_group_mapping definition

CREATE TABLE `account_group_mapping` (
  `id` int NOT NULL AUTO_INCREMENT,
  `account_group_id` int NOT NULL,
  `account_id` int NOT NULL,
  `is_active` tinyint(1) NOT NULL,
  `created_by` varchar(50) NOT NULL,
  `created_at` datetime NOT NULL,
  `updated_by` varchar(50) NOT NULL,
  `updated_at` datetime NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;


-- uzi_pdd.audit_log definition

CREATE TABLE `audit_log` (
  `id` int NOT NULL AUTO_INCREMENT,
  `pdd_txn_id` varchar(50) NOT NULL,
  `event` varchar(255) NOT NULL,
  `sub_event` varchar(255) DEFAULT NULL,
  `data` text,
  `data_json` json DEFAULT NULL,
  `created_at` datetime NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=3705991 DEFAULT CHARSET=latin1;


-- uzi_pdd.defect_group definition

CREATE TABLE `defect_group` (
  `key` varchar(50) NOT NULL,
  `title` varchar(50) NOT NULL,
  `is_agent_review_enabled` tinyint(1) NOT NULL DEFAULT '1',
  `is_ml_review_enabled` tinyint(1) NOT NULL DEFAULT '1',
  `is_active` tinyint(1) NOT NULL DEFAULT '1',
  `created_by` varchar(50) DEFAULT NULL,
  `created_at` datetime NOT NULL,
  `updated_by` varchar(50) DEFAULT NULL,
  `updated_at` datetime NOT NULL,
  PRIMARY KEY (`key`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;


-- uzi_pdd.dynamic_question_log definition

CREATE TABLE `dynamic_question_log` (
  `id` int NOT NULL AUTO_INCREMENT,
  `pdd_txn_id` varchar(255) NOT NULL,
  `imei` varchar(255) NOT NULL,
  `is_resolved` tinyint(1) NOT NULL DEFAULT '0',
  `volume_button` varchar(255) DEFAULT NULL,
  `volume_button_type` varchar(255) DEFAULT NULL,
  `head_phone_jack` varchar(255) DEFAULT NULL,
  `power_button` varchar(255) DEFAULT NULL,
  `charging_jack` varchar(255) DEFAULT NULL,
  `silent_button` varchar(255) DEFAULT NULL,
  `sim_tray` varchar(255) DEFAULT NULL,
  `front_camera_position` varchar(255) DEFAULT NULL,
  `back_camera_position` varchar(255) DEFAULT NULL,
  `brand_logo` varchar(255) DEFAULT NULL,
  `notch_camera_cutout` varchar(255) DEFAULT NULL,
  `finger_print_sensor` varchar(255) DEFAULT NULL,
  `num_of_back_camera` int DEFAULT NULL,
  `created_at` datetime NOT NULL,
  `created_by` varchar(255) NOT NULL,
  `updated_at` datetime NOT NULL,
  `updated_by` varchar(255) NOT NULL,
  PRIMARY KEY (`id`),
  KEY `dynamic_question_log_imei_index` (`imei`),
  KEY `dynamic_question_log_is_resolved_index` (`is_resolved`),
  KEY `dynamic_question_log_pdd_txn_id_index` (`pdd_txn_id`)
) ENGINE=InnoDB AUTO_INCREMENT=13 DEFAULT CHARSET=latin1;


-- uzi_pdd.flyway_schema_history definition

CREATE TABLE `flyway_schema_history` (
  `installed_rank` int NOT NULL,
  `version` varchar(50) DEFAULT NULL,
  `description` varchar(200) NOT NULL,
  `type` varchar(20) NOT NULL,
  `script` varchar(1000) NOT NULL,
  `checksum` int DEFAULT NULL,
  `installed_by` varchar(100) NOT NULL,
  `installed_on` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
  `execution_time` int NOT NULL,
  `success` tinyint(1) NOT NULL,
  PRIMARY KEY (`installed_rank`),
  KEY `flyway_schema_history_s_idx` (`success`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;


-- uzi_pdd.global_config_type definition

CREATE TABLE `global_config_type` (
  `key` varchar(255) NOT NULL,
  `title` varchar(255) NOT NULL,
  `active` tinyint(1) DEFAULT '1',
  `created_by` varchar(50) DEFAULT NULL,
  `created_at` datetime NOT NULL,
  `updated_by` varchar(50) DEFAULT NULL,
  `updated_at` datetime NOT NULL,
  PRIMARY KEY (`key`),
  UNIQUE KEY `key` (`key`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;


-- uzi_pdd.mode definition

CREATE TABLE `mode` (
  `key` varchar(50) NOT NULL,
  `title` varchar(50) NOT NULL,
  `created_by` varchar(50) NOT NULL,
  `created_at` datetime NOT NULL,
  `updated_by` varchar(50) DEFAULT NULL,
  `updated_at` datetime NOT NULL,
  PRIMARY KEY (`key`),
  UNIQUE KEY `title` (`title`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;


-- uzi_pdd.part_variation definition

CREATE TABLE `part_variation` (
  `id` int NOT NULL,
  `part_id` int NOT NULL,
  `label` varchar(1000) DEFAULT NULL,
  `priority` int DEFAULT NULL,
  `variation_key` varchar(255) DEFAULT NULL,
  `ml_min_threshold_value` int NOT NULL DEFAULT '20',
  `is_active` tinyint(1) DEFAULT '1',
  `created_by` varchar(50) DEFAULT 'CODE',
  `updated_by` varchar(50) DEFAULT 'CODE',
  `created_at` datetime DEFAULT CURRENT_TIMESTAMP,
  `updated_at` datetime DEFAULT CURRENT_TIMESTAMP,
  `ml_max_threshold_value` int NOT NULL DEFAULT '70',
  PRIMARY KEY (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;


-- uzi_pdd.agent definition

CREATE TABLE `agent` (
  `id` int NOT NULL AUTO_INCREMENT,
  `account_key` varchar(50) NOT NULL,
  `password` varchar(50) NOT NULL,
  `email` varchar(50) NOT NULL,
  `mobile` varchar(50) NOT NULL,
  `full_name` varchar(50) NOT NULL,
  `is_active` tinyint(1) NOT NULL,
  `created_by` varchar(50) NOT NULL,
  `created_at` datetime NOT NULL,
  `uzi_updated` timestamp NULL DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP,
  PRIMARY KEY (`id`),
  UNIQUE KEY `email` (`email`),
  UNIQUE KEY `mobile` (`mobile`),
  KEY `account_key` (`account_key`),
  KEY `uzi_updated` (`uzi_updated`),
  CONSTRAINT `agent_fk_account_key` FOREIGN KEY (`account_key`) REFERENCES `account` (`key`) ON DELETE RESTRICT ON UPDATE RESTRICT
) ENGINE=InnoDB AUTO_INCREMENT=182 DEFAULT CHARSET=latin1;


-- uzi_pdd.agent_ext definition

CREATE TABLE `agent_ext` (
  `agent_id` int NOT NULL,
  `socket_id` varchar(50) DEFAULT NULL,
  `is_connected` tinyint(1) DEFAULT '1',
  `android_token` text,
  `ios_token` text,
  `web_token` text,
  PRIMARY KEY (`agent_id`),
  UNIQUE KEY `socket_id` (`socket_id`),
  KEY `agent_id` (`agent_id`),
  CONSTRAINT `agent_ext_fk_agent_id` FOREIGN KEY (`agent_id`) REFERENCES `agent` (`id`) ON DELETE RESTRICT ON UPDATE RESTRICT
) ENGINE=InnoDB DEFAULT CHARSET=latin1;


-- uzi_pdd.agent_session definition

CREATE TABLE `agent_session` (
  `id` int NOT NULL AUTO_INCREMENT,
  `socket_id` varchar(50) DEFAULT NULL,
  `agent_id` int NOT NULL,
  `connected_at` datetime NOT NULL,
  `disconnected_at` datetime DEFAULT NULL,
  `created_by` varchar(50) NOT NULL,
  `created_at` datetime NOT NULL,
  PRIMARY KEY (`id`),
  KEY `agent_id` (`agent_id`),
  CONSTRAINT `agent_session_fk_agent_id` FOREIGN KEY (`agent_id`) REFERENCES `agent` (`id`) ON DELETE RESTRICT ON UPDATE RESTRICT
) ENGINE=InnoDB AUTO_INCREMENT=207 DEFAULT CHARSET=latin1;


-- uzi_pdd.defect definition

CREATE TABLE `defect` (
  `key` varchar(255) NOT NULL,
  `title` varchar(255) NOT NULL,
  `defect_group_key` varchar(50) NOT NULL,
  `part_id` int DEFAULT NULL,
  `priority` int DEFAULT NULL,
  `ml_min_threshold_value` int NOT NULL DEFAULT '20',
  `ml_max_threshold_value` int NOT NULL DEFAULT '70',
  `is_active` tinyint(1) DEFAULT '1',
  `created_by` varchar(50) DEFAULT NULL,
  `created_at` datetime NOT NULL,
  `updated_by` varchar(50) DEFAULT NULL,
  `updated_at` datetime NOT NULL,
  PRIMARY KEY (`key`),
  UNIQUE KEY `key` (`key`),
  KEY `defect_group_key` (`defect_group_key`),
  CONSTRAINT `defect_fk_defect_group_key` FOREIGN KEY (`defect_group_key`) REFERENCES `defect_group` (`key`) ON DELETE RESTRICT ON UPDATE RESTRICT
) ENGINE=InnoDB DEFAULT CHARSET=latin1;


-- uzi_pdd.global_config definition

CREATE TABLE `global_config` (
  `id` int NOT NULL AUTO_INCREMENT,
  `mode_key` varchar(255) NOT NULL,
  `global_config_type_key` varchar(255) NOT NULL,
  `ml_validation_enabled` tinyint(1) NOT NULL DEFAULT '1',
  `config` text NOT NULL,
  `active` tinyint(1) DEFAULT '1',
  `created_by` varchar(50) DEFAULT NULL,
  `created_at` datetime NOT NULL,
  `updated_by` varchar(50) DEFAULT NULL,
  `updated_at` datetime NOT NULL,
  PRIMARY KEY (`id`),
  UNIQUE KEY `mode_key_uniq_type_key_uniq_global_config_type_key` (`mode_key`,`global_config_type_key`),
  KEY `mode_key` (`mode_key`),
  KEY `global_config_type_key` (`global_config_type_key`),
  CONSTRAINT `global_config_fk_global_config_type_key` FOREIGN KEY (`global_config_type_key`) REFERENCES `global_config_type` (`key`) ON DELETE RESTRICT ON UPDATE RESTRICT,
  CONSTRAINT `global_config_fk_mode_key` FOREIGN KEY (`mode_key`) REFERENCES `mode` (`key`) ON DELETE RESTRICT ON UPDATE RESTRICT
) ENGINE=InnoDB AUTO_INCREMENT=36 DEFAULT CHARSET=latin1;


-- uzi_pdd.global_config_default_value definition

CREATE TABLE `global_config_default_value` (
  `id` int NOT NULL AUTO_INCREMENT,
  `key` varchar(255) NOT NULL,
  `value` int NOT NULL,
  `global_config_type_key` varchar(255) NOT NULL,
  `active` tinyint(1) DEFAULT '1',
  `created_by` varchar(50) DEFAULT NULL,
  `created_at` datetime NOT NULL,
  `updated_by` varchar(50) DEFAULT NULL,
  `updated_at` datetime NOT NULL,
  PRIMARY KEY (`id`),
  KEY `global_config_type_key` (`global_config_type_key`),
  CONSTRAINT `global_config_default_value_fk_global_config_type_key` FOREIGN KEY (`global_config_type_key`) REFERENCES `global_config_type` (`key`) ON DELETE RESTRICT ON UPDATE RESTRICT
) ENGINE=InnoDB AUTO_INCREMENT=4 DEFAULT CHARSET=latin1;


-- uzi_pdd.pd_dynamic_defect_mapping definition

CREATE TABLE `pd_dynamic_defect_mapping` (
  `id` int NOT NULL AUTO_INCREMENT,
  `pd_masked_key` varchar(50) NOT NULL,
  `pd_masked_name` varchar(255) DEFAULT NULL,
  `defect_key` varchar(255) NOT NULL,
  `active` tinyint(1) NOT NULL DEFAULT '1',
  `created_at` datetime NOT NULL,
  `created_by` varchar(50) DEFAULT NULL,
  `updated_at` datetime NOT NULL,
  `updated_by` varchar(50) DEFAULT NULL,
  PRIMARY KEY (`id`),
  UNIQUE KEY `defect_key` (`defect_key`),
  CONSTRAINT `pd_dynamic_defect_mapping_fk_defect_key` FOREIGN KEY (`defect_key`) REFERENCES `defect` (`key`)
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=latin1;


-- uzi_pdd.pdd_config definition

CREATE TABLE `pdd_config` (
  `id` int NOT NULL AUTO_INCREMENT,
  `account_key` varchar(50) NOT NULL,
  `mode_key` varchar(50) NOT NULL,
  `ml_validation_enabled` tinyint(1) DEFAULT '1',
  `config_json` text NOT NULL,
  `max_agent_review_count` int NOT NULL DEFAULT '3',
  `created_by` varchar(50) DEFAULT NULL,
  `created_at` datetime NOT NULL,
  `updated_by` varchar(50) DEFAULT NULL,
  `updated_at` datetime NOT NULL,
  PRIMARY KEY (`id`),
  UNIQUE KEY `account_key_uniq_mode_key` (`account_key`,`mode_key`),
  KEY `account_key` (`account_key`),
  KEY `mode_key` (`mode_key`),
  CONSTRAINT `pdd_config_fk_account_key` FOREIGN KEY (`account_key`) REFERENCES `account` (`key`) ON DELETE RESTRICT ON UPDATE RESTRICT,
  CONSTRAINT `pdd_config_fk_mode_key` FOREIGN KEY (`mode_key`) REFERENCES `mode` (`key`) ON DELETE RESTRICT ON UPDATE RESTRICT
) ENGINE=InnoDB AUTO_INCREMENT=49 DEFAULT CHARSET=latin1;


-- uzi_pdd.pdd_config_defect_group definition

CREATE TABLE `pdd_config_defect_group` (
  `id` int NOT NULL AUTO_INCREMENT,
  `pdd_config_id` int NOT NULL,
  `defect_group_key` varchar(50) NOT NULL,
  `is_active` tinyint(1) NOT NULL,
  `created_at` datetime NOT NULL,
  `created_by` varchar(255) NOT NULL,
  `updated_at` datetime NOT NULL,
  `updated_by` varchar(255) NOT NULL,
  PRIMARY KEY (`id`),
  UNIQUE KEY `pdd_config_defect_group_pdd_config_id_defect_group_key_uindex` (`pdd_config_id`,`defect_group_key`),
  KEY `pdd_config_defect_group_defect_group_key_fk` (`defect_group_key`),
  KEY `pdd_config_defect_group_is_active_index` (`is_active`),
  CONSTRAINT `pdd_config_defect_group_defect_group_key_fk` FOREIGN KEY (`defect_group_key`) REFERENCES `defect_group` (`key`),
  CONSTRAINT `pdd_config_defect_group_pdd_config_id_fk` FOREIGN KEY (`pdd_config_id`) REFERENCES `pdd_config` (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=7 DEFAULT CHARSET=latin1;


-- uzi_pdd.pdd_order definition

CREATE TABLE `pdd_order` (
  `id` int NOT NULL AUTO_INCREMENT,
  `pdd_txn_id` varchar(50) NOT NULL,
  `parent_txn_id` varchar(50) DEFAULT NULL,
  `account_key` varchar(50) NOT NULL,
  `mode_key` varchar(50) NOT NULL,
  `overall_status` enum('NONE','YES','NO','RETRY') DEFAULT NULL,
  `current_state` varchar(255) DEFAULT NULL,
  `response` json DEFAULT NULL,
  `retry_clone_status` tinyint(1) DEFAULT '0',
  `secondary_key` varchar(50) DEFAULT NULL,
  `imei1` varchar(255) DEFAULT NULL,
  `imei2` varchar(255) DEFAULT NULL,
  `created_by` varchar(50) DEFAULT NULL,
  `created_at` datetime NOT NULL,
  `updated_by` varchar(50) DEFAULT NULL,
  `updated_at` datetime NOT NULL,
  PRIMARY KEY (`id`),
  UNIQUE KEY `pdd_txn_id` (`pdd_txn_id`),
  KEY `account_key` (`account_key`),
  KEY `mode_key` (`mode_key`),
  CONSTRAINT `pdd_order_fk_account_key` FOREIGN KEY (`account_key`) REFERENCES `account` (`key`) ON DELETE RESTRICT ON UPDATE RESTRICT,
  CONSTRAINT `pdd_order_fk_mode_key` FOREIGN KEY (`mode_key`) REFERENCES `mode` (`key`) ON DELETE RESTRICT ON UPDATE RESTRICT
) ENGINE=InnoDB AUTO_INCREMENT=9933 DEFAULT CHARSET=latin1;


-- uzi_pdd.pdd_order_image definition

CREATE TABLE `pdd_order_image` (
  `id` int NOT NULL AUTO_INCREMENT,
  `pdd_order_id` int NOT NULL,
  `defect_group_key` varchar(50) NOT NULL,
  `thumbnail_image_url` varchar(255) DEFAULT NULL,
  `full_image_url` varchar(255) DEFAULT NULL,
  `full_cropped_image_url` varchar(255) DEFAULT NULL,
  `image_key` varchar(50) DEFAULT NULL,
  `validation_status` varchar(255) DEFAULT NULL,
  `extra_info` text,
  `quad_info` json DEFAULT NULL,
  `extra_info_full_image` text,
  `created_by` varchar(50) DEFAULT NULL,
  `created_at` datetime NOT NULL,
  `updated_at` datetime DEFAULT NULL,
  `updated_by` varchar(50) DEFAULT NULL,
  PRIMARY KEY (`id`),
  KEY `pdd_order_id` (`pdd_order_id`),
  KEY `defect_group_key` (`defect_group_key`),
  CONSTRAINT `pdd_order_image_fk_defect_group_key` FOREIGN KEY (`defect_group_key`) REFERENCES `defect_group` (`key`) ON DELETE RESTRICT ON UPDATE RESTRICT,
  CONSTRAINT `pdd_order_image_fk_pdd_order_id` FOREIGN KEY (`pdd_order_id`) REFERENCES `pdd_order` (`id`) ON DELETE RESTRICT ON UPDATE RESTRICT
) ENGINE=InnoDB AUTO_INCREMENT=16728 DEFAULT CHARSET=latin1;


-- uzi_pdd.pdd_order_image_ext definition

CREATE TABLE `pdd_order_image_ext` (
  `pdd_order_image_id` int NOT NULL,
  `pdd_txn_id` varchar(255) NOT NULL,
  `thumbnail_extra_info` json DEFAULT NULL,
  `ml_response_extra_info` json DEFAULT NULL,
  `uzi_updated` timestamp NULL DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP,
  PRIMARY KEY (`pdd_order_image_id`),
  KEY `pdd_order_image_id` (`pdd_order_image_id`),
  KEY `uzi_updated` (`uzi_updated`),
  CONSTRAINT `pdd_order_image_ext_fk_pdd_order_image_id` FOREIGN KEY (`pdd_order_image_id`) REFERENCES `pdd_order_image` (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;


-- uzi_pdd.account_defect definition

CREATE TABLE `account_defect` (
  `id` int NOT NULL AUTO_INCREMENT,
  `account_key` varchar(255) NOT NULL,
  `mode_key` varchar(255) NOT NULL,
  `defect_key` varchar(255) NOT NULL,
  `ml_min_threshold_value` int NOT NULL DEFAULT '50',
  `ml_max_threshold_value` int NOT NULL DEFAULT '50',
  `agent_threshold_value` int DEFAULT '50',
  `active` tinyint(1) DEFAULT '1',
  `created_by` varchar(50) DEFAULT NULL,
  `created_at` datetime NOT NULL,
  `updated_by` varchar(50) DEFAULT NULL,
  `updated_at` datetime NOT NULL,
  PRIMARY KEY (`id`),
  UNIQUE KEY `account_key_uniq_mode_key_uniq_defect_key` (`account_key`,`mode_key`,`defect_key`),
  KEY `account_key` (`account_key`),
  KEY `mode_key` (`mode_key`),
  KEY `defect_key` (`defect_key`),
  CONSTRAINT `account_defect_fk_account_key` FOREIGN KEY (`account_key`) REFERENCES `account` (`key`) ON DELETE RESTRICT ON UPDATE RESTRICT,
  CONSTRAINT `account_defect_fk_defect_key` FOREIGN KEY (`defect_key`) REFERENCES `defect` (`key`) ON DELETE RESTRICT ON UPDATE RESTRICT,
  CONSTRAINT `account_defect_fk_mode_key` FOREIGN KEY (`mode_key`) REFERENCES `mode` (`key`) ON DELETE RESTRICT ON UPDATE RESTRICT
) ENGINE=InnoDB AUTO_INCREMENT=3 DEFAULT CHARSET=latin1;


-- uzi_pdd.ml_processing_status definition

CREATE TABLE `ml_processing_status` (
  `id` int NOT NULL AUTO_INCREMENT,
  `pdd_order_id` int NOT NULL,
  `defect_group_key` varchar(50) NOT NULL,
  `status` varchar(50) NOT NULL,
  `ml_callback_status` varchar(255) NOT NULL DEFAULT 'timeout',
  `response_time_sec` int DEFAULT NULL,
  `description` text,
  `created_by` varchar(50) DEFAULT NULL,
  `updated_by` varchar(50) DEFAULT NULL,
  `created_at` datetime NOT NULL,
  `updated_at` datetime NOT NULL,
  PRIMARY KEY (`id`),
  UNIQUE KEY `pdd_order_id_uniq_defect_group_key` (`pdd_order_id`,`defect_group_key`),
  KEY `pdd_order_id` (`pdd_order_id`),
  KEY `defect_group_key` (`defect_group_key`),
  CONSTRAINT `ml_processing_status_fk_defect_group_key` FOREIGN KEY (`defect_group_key`) REFERENCES `defect_group` (`key`) ON DELETE RESTRICT ON UPDATE RESTRICT,
  CONSTRAINT `ml_processing_status_fk_pdd_order_id` FOREIGN KEY (`pdd_order_id`) REFERENCES `pdd_order` (`id`) ON DELETE RESTRICT ON UPDATE RESTRICT
) ENGINE=InnoDB AUTO_INCREMENT=7965 DEFAULT CHARSET=latin1;


-- uzi_pdd.pdd_agent_defect_result definition

CREATE TABLE `pdd_agent_defect_result` (
  `id` int NOT NULL AUTO_INCREMENT,
  `pdd_order_id` int NOT NULL,
  `pdd_txn_id` varchar(50) NOT NULL,
  `defect_key` varchar(255) DEFAULT NULL,
  `defect_group` varchar(50) DEFAULT NULL,
  `overall_agent_review_status` enum('NONE','YES','NO') NOT NULL DEFAULT 'NONE',
  `part_variation_id` int DEFAULT NULL,
  `defect_rect_data` text,
  `result_image_url` varchar(255) DEFAULT NULL,
  `created_by` varchar(50) DEFAULT NULL,
  `created_at` datetime NOT NULL,
  `updated_by` varchar(50) DEFAULT NULL,
  `updated_at` datetime NOT NULL,
  PRIMARY KEY (`id`),
  KEY `pdd_order_id` (`pdd_order_id`),
  KEY `defect_key` (`defect_key`),
  CONSTRAINT `pdd_agent_defect_result_fk_defect_key` FOREIGN KEY (`defect_key`) REFERENCES `defect` (`key`) ON DELETE RESTRICT ON UPDATE RESTRICT,
  CONSTRAINT `pdd_agent_defect_result_fk_pdd_order_id` FOREIGN KEY (`pdd_order_id`) REFERENCES `pdd_order` (`id`) ON DELETE RESTRICT ON UPDATE RESTRICT
) ENGINE=InnoDB AUTO_INCREMENT=128250 DEFAULT CHARSET=latin1;


-- uzi_pdd.pdd_agent_defect_review definition

CREATE TABLE `pdd_agent_defect_review` (
  `id` int NOT NULL AUTO_INCREMENT,
  `pdd_order_id` int NOT NULL,
  `pdd_txn_id` varchar(50) NOT NULL,
  `agent_id` int NOT NULL,
  `defect_key` varchar(255) DEFAULT NULL,
  `defect_group` varchar(50) DEFAULT NULL,
  `agent_review` enum('NONE','YES','NO') NOT NULL DEFAULT 'NONE',
  `part_variation_id` int DEFAULT NULL,
  `defect_rect_data` text,
  `result_image_url` varchar(255) DEFAULT NULL,
  `extra_info` text,
  `created_by` varchar(50) DEFAULT NULL,
  `created_at` datetime NOT NULL,
  `updated_by` varchar(50) DEFAULT NULL,
  `updated_at` datetime NOT NULL,
  `uzi_updated` timestamp NULL DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP,
  PRIMARY KEY (`id`),
  UNIQUE KEY `pdd_order_id_uniq_defect_group_uniq_defect_key_uniq_agent_id` (`pdd_order_id`,`defect_group`,`defect_key`,`agent_id`),
  KEY `pdd_order_id` (`pdd_order_id`),
  KEY `defect_key` (`defect_key`),
  KEY `agent_id` (`agent_id`),
  KEY `uzi_updated` (`uzi_updated`),
  CONSTRAINT `pdd_agent_defect_review_fk_agent_id` FOREIGN KEY (`agent_id`) REFERENCES `agent` (`id`) ON DELETE RESTRICT ON UPDATE RESTRICT,
  CONSTRAINT `pdd_agent_defect_review_fk_defect_key` FOREIGN KEY (`defect_key`) REFERENCES `defect` (`key`) ON DELETE RESTRICT ON UPDATE RESTRICT,
  CONSTRAINT `pdd_agent_defect_review_fk_pdd_order_id` FOREIGN KEY (`pdd_order_id`) REFERENCES `pdd_order` (`id`) ON DELETE RESTRICT ON UPDATE RESTRICT
) ENGINE=InnoDB AUTO_INCREMENT=47761 DEFAULT CHARSET=latin1;


-- uzi_pdd.pdd_ml_defect_part_variation_review definition

CREATE TABLE `pdd_ml_defect_part_variation_review` (
  `id` int NOT NULL AUTO_INCREMENT,
  `pdd_order_id` int NOT NULL,
  `pdd_txn_id` varchar(255) NOT NULL,
  `defect_key` varchar(255) NOT NULL,
  `part_variation_key` varchar(255) NOT NULL,
  `part_id` int NOT NULL,
  `part_variation_id` int NOT NULL,
  `ml_review_score` int NOT NULL DEFAULT '-1',
  `status` varchar(255) DEFAULT NULL,
  `result_image_url` varchar(255) DEFAULT NULL,
  `extra_info` text,
  `created_by` varchar(50) DEFAULT NULL,
  `created_at` datetime NOT NULL,
  `updated_by` varchar(50) DEFAULT NULL,
  `updated_at` datetime NOT NULL,
  PRIMARY KEY (`id`),
  KEY `pdd_order_id` (`pdd_order_id`),
  KEY `defect_key` (`defect_key`),
  CONSTRAINT `pdd_ml_defect_part_variation_review_fk_defect_key` FOREIGN KEY (`defect_key`) REFERENCES `defect` (`key`),
  CONSTRAINT `pdd_ml_defect_part_variation_review_fk_pdd_order_id` FOREIGN KEY (`pdd_order_id`) REFERENCES `pdd_order` (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=6426 DEFAULT CHARSET=latin1;


-- uzi_pdd.pdd_ml_defect_result definition

CREATE TABLE `pdd_ml_defect_result` (
  `id` int NOT NULL AUTO_INCREMENT,
  `pdd_order_id` int NOT NULL,
  `pdd_txn_id` varchar(255) NOT NULL,
  `defect_key` varchar(255) NOT NULL,
  `part_id` int DEFAULT NULL,
  `ml_review_score` int NOT NULL DEFAULT '-1',
  `push_agent_status` varchar(255) DEFAULT NULL,
  `min_threshold` int DEFAULT NULL,
  `max_threshold` int DEFAULT NULL,
  `status` varchar(255) DEFAULT NULL,
  `threshold_crossed` tinyint(1) DEFAULT NULL,
  `part_variation_id` int DEFAULT NULL,
  `result_image_url` varchar(255) DEFAULT NULL,
  `extra_info` text,
  `created_by` varchar(50) DEFAULT NULL,
  `created_at` datetime NOT NULL,
  `updated_by` varchar(50) DEFAULT NULL,
  `updated_at` datetime NOT NULL,
  PRIMARY KEY (`id`),
  UNIQUE KEY `pdd_order_id_uniq_defect_key` (`pdd_order_id`,`defect_key`),
  KEY `pdd_order_id` (`pdd_order_id`),
  KEY `defect_key` (`defect_key`),
  CONSTRAINT `pdd_ml_defect_result_fk_defect_key` FOREIGN KEY (`defect_key`) REFERENCES `defect` (`key`) ON DELETE RESTRICT ON UPDATE RESTRICT,
  CONSTRAINT `pdd_ml_defect_result_fk_pdd_order_id` FOREIGN KEY (`pdd_order_id`) REFERENCES `pdd_order` (`id`) ON DELETE RESTRICT ON UPDATE RESTRICT
) ENGINE=InnoDB AUTO_INCREMENT=73771 DEFAULT CHARSET=latin1;


