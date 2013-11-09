# [liveSense :: Framework :: ApacheDS - org.liveSense.framework.apacheds](http://github.com/liveSense/org.liveSense.framework.apacheds)

## Description
ApacheDS is an embbedable directory server entirely written in Java, which has been certified LDAPv3 compatible by the Open Group. Besides LDAP it supports Kerberos 5 and the Change Password Protocol. It has been designed to introduce triggers, stored procedures, queues and views to the world of LDAP which has lacked these rich constructs.

## OSGi Exported packages
* jdbm(2.0.0.M1)
* jdbm.btree(2.0.0.M1)
* jdbm.helper(2.0.0.M1)
* jdbm.htree(2.0.0.M1)
* jdbm.recman(2.0.0.M1)
* org.apache.directory.api.asn1(1.0.0.M14)
* org.apache.directory.api.asn1.actions(1.0.0.M14)
* org.apache.directory.api.asn1.ber(1.0.0.M14)
* org.apache.directory.api.asn1.ber.grammar(1.0.0.M14)
* org.apache.directory.api.asn1.ber.tlv(1.0.0.M14)
* org.apache.directory.api.asn1.util(1.0.0.M14)
* org.apache.directory.api.i18n(1.0.0.M14)
* org.apache.directory.api.ldap.aci(1.0.0.M14)
* org.apache.directory.api.ldap.aci.protectedItem(1.0.0.M14)
* org.apache.directory.api.ldap.codec(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.abandonRequest(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.addRequest(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.addResponse(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.bindRequest(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.bindResponse(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.compareRequest(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.compareResponse(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.controls(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.delRequest(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.delResponse(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.extendedRequest(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.extendedResponse(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.intermediateResponse(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.ldapMessage(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.ldapResult(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.modifyDnRequest(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.modifyDnResponse(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.modifyRequest(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.modifyResponse(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.searchRequest(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.searchRequest.filter(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.searchResultDone(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.searchResultEntry(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.searchResultReference(1.0.0.M14)
* org.apache.directory.api.ldap.codec.actions.unbindRequest(1.0.0.M14)
* org.apache.directory.api.ldap.codec.api(1.0.0.M14)
* org.apache.directory.api.ldap.codec.controls.cascade(1.0.0.M14)
* org.apache.directory.api.ldap.codec.controls.manageDsaIT(1.0.0.M14)
* org.apache.directory.api.ldap.codec.controls.search.entryChange(1.0.0.M14)
* org.apache.directory.api.ldap.codec.controls.search.pagedSearch(1.0.0.M14)
* org.apache.directory.api.ldap.codec.controls.search.persistentSearch(1.0.0.M14)
* org.apache.directory.api.ldap.codec.controls.search.subentries(1.0.0.M14)
* org.apache.directory.api.ldap.codec.decorators(1.0.0.M14)
* org.apache.directory.api.ldap.codec.osgi(1.0.0.M14)
* org.apache.directory.api.ldap.codec.protocol.mina(1.0.0.M14)
* org.apache.directory.api.ldap.codec.search(1.0.0.M14)
* org.apache.directory.api.ldap.codec.standalone(1.0.0.M14)
* org.apache.directory.api.ldap.extras(1.0.0.M14)
* org.apache.directory.api.ldap.extras.controls(1.0.0.M14)
* org.apache.directory.api.ldap.extras.controls.ppolicy(1.0.0.M14)
* org.apache.directory.api.ldap.extras.controls.ppolicy_impl(1.0.0.M14)
* org.apache.directory.api.ldap.extras.controls.syncrepl_impl(1.0.0.M14)
* org.apache.directory.api.ldap.extras.extended(1.0.0.M14)
* org.apache.directory.api.ldap.extras.extended.ads_impl.cancel(1.0.0.M14)
* org.apache.directory.api.ldap.extras.extended.ads_impl.certGeneration(1.0.0.M14)
* org.apache.directory.api.ldap.extras.extended.ads_impl.gracefulDisconnect(1.0.0.M14)
* org.apache.directory.api.ldap.extras.extended.ads_impl.gracefulShutdown(1.0.0.M14)
* org.apache.directory.api.ldap.extras.extended.ads_impl.storedProcedure(1.0.0.M14)
* org.apache.directory.api.ldap.model.constants(1.0.0.M14)
* org.apache.directory.api.ldap.model.csn(1.0.0.M14)
* org.apache.directory.api.ldap.model.cursor(1.0.0.M14)
* org.apache.directory.api.ldap.model.entry(1.0.0.M14)
* org.apache.directory.api.ldap.model.exception(1.0.0.M14)
* org.apache.directory.api.ldap.model.filter(1.0.0.M14)
* org.apache.directory.api.ldap.model.ldif(1.0.0.M14)
* org.apache.directory.api.ldap.model.message(1.0.0.M14)
* org.apache.directory.api.ldap.model.message.controls(1.0.0.M14)
* org.apache.directory.api.ldap.model.message.extended(1.0.0.M14)
* org.apache.directory.api.ldap.model.name(1.0.0.M14)
* org.apache.directory.api.ldap.model.password(1.0.0.M14)
* org.apache.directory.api.ldap.model.schema(1.0.0.M14)
* org.apache.directory.api.ldap.model.schema.comparators(1.0.0.M14)
* org.apache.directory.api.ldap.model.schema.normalizers(1.0.0.M14)
* org.apache.directory.api.ldap.model.schema.parsers(1.0.0.M14)
* org.apache.directory.api.ldap.model.schema.registries(1.0.0.M14)
* org.apache.directory.api.ldap.model.schema.registries.helper(1.0.0.M14)
* org.apache.directory.api.ldap.model.schema.syntaxCheckers(1.0.0.M14)
* org.apache.directory.api.ldap.model.schema.syntaxes(1.0.0.M14)
* org.apache.directory.api.ldap.model.subtree(1.0.0.M14)
* org.apache.directory.api.ldap.model.url(1.0.0.M14)
* org.apache.directory.api.ldap.schemaextractor(1.0.0.M14)
* org.apache.directory.api.ldap.schemaextractor.impl(1.0.0.M14)
* org.apache.directory.api.ldap.schemaloader(1.0.0.M14)
* org.apache.directory.api.ldap.schemamanager.impl(1.0.0.M14)
* org.apache.directory.api.ldap.sp(1.0.0.M14)
* org.apache.directory.api.ldap.trigger(1.0.0.M14)
* org.apache.directory.api.ldap.util(1.0.0.M14)
* org.apache.directory.api.ldap.util.tree(1.0.0.M14)
* org.apache.directory.api.util(1.0.0.M14)
* org.apache.directory.api.util.exception(1.0.0.M14)
* org.apache.directory.ldap.client.api(1.0.0.M14)
* org.apache.directory.ldap.client.api.callback(1.0.0.M14)
* org.apache.directory.ldap.client.api.exception(1.0.0.M14)
* org.apache.directory.ldap.client.api.future(1.0.0.M14)
* org.apache.directory.server.bridge.http(2.0.0.M9)
* org.apache.directory.server.config(2.0.0.M9)
* org.apache.directory.server.config.beans(2.0.0.M9)
* org.apache.directory.server.config.builder(2.0.0.M9)
* org.apache.directory.server.configuration(2.0.0.M9)
* org.apache.directory.server.constants(2.0.0.M9)
* org.apache.directory.server.core(2.0.0.M9)
* org.apache.directory.server.core.admin(2.0.0.M9)
* org.apache.directory.server.core.api(2.0.0.M9)
* org.apache.directory.server.core.api.administrative(2.0.0.M9)
* org.apache.directory.server.core.api.authn.ppolicy(2.0.0.M9)
* org.apache.directory.server.core.api.changelog(2.0.0.M9)
* org.apache.directory.server.core.api.entry(2.0.0.M9)
* org.apache.directory.server.core.api.event(2.0.0.M9)
* org.apache.directory.server.core.api.filtering(2.0.0.M9)
* org.apache.directory.server.core.api.interceptor(2.0.0.M9)
* org.apache.directory.server.core.api.interceptor.context(2.0.0.M9)
* org.apache.directory.server.core.api.journal(2.0.0.M9)
* org.apache.directory.server.core.api.normalization(2.0.0.M9)
* org.apache.directory.server.core.api.partition(2.0.0.M9)
* org.apache.directory.server.core.api.schema(2.0.0.M9)
* org.apache.directory.server.core.api.schema.registries.synchronizers(2.0.0.M9)
* org.apache.directory.server.core.api.sp(2.0.0.M9)
* org.apache.directory.server.core.api.sp.java(2.0.0.M9)
* org.apache.directory.server.core.api.subtree(2.0.0.M9)
* org.apache.directory.server.core.authn(2.0.0.M9)
* org.apache.directory.server.core.authn.ppolicy(2.0.0.M9)
* org.apache.directory.server.core.authz(2.0.0.M9)
* org.apache.directory.server.core.authz.support(2.0.0.M9)
* org.apache.directory.server.core.avltree(2.0.0.M9)
* org.apache.directory.server.core.avltree.avl(2.0.0.M9)
* org.apache.directory.server.core.changelog(2.0.0.M9)
* org.apache.directory.server.core.collective(2.0.0.M9)
* org.apache.directory.server.core.event(2.0.0.M9)
* org.apache.directory.server.core.exception(2.0.0.M9)
* org.apache.directory.server.core.hash(2.0.0.M9)
* org.apache.directory.server.core.jndi(2.0.0.M9)
* org.apache.directory.server.core.journal(2.0.0.M9)
* org.apache.directory.server.core.kerberos(2.0.0.M9)
* org.apache.directory.server.core.normalization(2.0.0.M9)
* org.apache.directory.server.core.operational(2.0.0.M9)
* org.apache.directory.server.core.partition.impl.avl(2.0.0.M9)
* org.apache.directory.server.core.partition.impl.btree(2.0.0.M9)
* org.apache.directory.server.core.partition.impl.btree.jdbm(2.0.0.M9)
* org.apache.directory.server.core.partition.ldif(2.0.0.M9)
* org.apache.directory.server.core.prefs(2.0.0.M9)
* org.apache.directory.server.core.referral(2.0.0.M9)
* org.apache.directory.server.core.schema(2.0.0.M9)
* org.apache.directory.server.core.security(2.0.0.M9)
* org.apache.directory.server.core.shared(2.0.0.M9)
* org.apache.directory.server.core.shared.partition(2.0.0.M9)
* org.apache.directory.server.core.subtree(2.0.0.M9)
* org.apache.directory.server.core.trigger(2.0.0.M9)
* org.apache.directory.server.dhcp(2.0.0.M9)
* org.apache.directory.server.dhcp.io(2.0.0.M9)
* org.apache.directory.server.dhcp.messages(2.0.0.M9)
* org.apache.directory.server.dhcp.options(2.0.0.M9)
* org.apache.directory.server.dhcp.options.dhcp(2.0.0.M9)
* org.apache.directory.server.dhcp.options.linklayer(2.0.0.M9)
* org.apache.directory.server.dhcp.options.misc(2.0.0.M9)
* org.apache.directory.server.dhcp.options.perhost(2.0.0.M9)
* org.apache.directory.server.dhcp.options.perinterface(2.0.0.M9)
* org.apache.directory.server.dhcp.options.tcp(2.0.0.M9)
* org.apache.directory.server.dhcp.options.vendor(2.0.0.M9)
* org.apache.directory.server.dhcp.protocol(2.0.0.M9)
* org.apache.directory.server.dhcp.service(2.0.0.M9)
* org.apache.directory.server.dhcp.store(2.0.0.M9)
* org.apache.directory.server.dns(2.0.0.M9)
* org.apache.directory.server.dns.io.decoder(2.0.0.M9)
* org.apache.directory.server.dns.io.encoder(2.0.0.M9)
* org.apache.directory.server.dns.messages(2.0.0.M9)
* org.apache.directory.server.dns.protocol(2.0.0.M9)
* org.apache.directory.server.dns.service(2.0.0.M9)
* org.apache.directory.server.dns.store(2.0.0.M9)
* org.apache.directory.server.dns.store.jndi(2.0.0.M9)
* org.apache.directory.server.dns.store.jndi.operations(2.0.0.M9)
* org.apache.directory.server.dns.util(2.0.0.M9)
* org.apache.directory.server.i18n(2.0.0.M9)
* org.apache.directory.server.integration.http(2.0.0.M9)
* org.apache.directory.server.kerberos.kdc(2.0.0.M9)
* org.apache.directory.server.kerberos.kdc.authentication(2.0.0.M9)
* org.apache.directory.server.kerberos.kdc.ticketgrant(2.0.0.M9)
* org.apache.directory.server.kerberos.protocol(2.0.0.M9)
* org.apache.directory.server.kerberos.protocol.codec(2.0.0.M9)
* org.apache.directory.server.kerberos.sam(2.0.0.M9)
* org.apache.directory.server.kerberos.shared.crypto.checksum(2.0.0.M9)
* org.apache.directory.server.kerberos.shared.crypto.encryption(2.0.0.M9)
* org.apache.directory.server.kerberos.shared.keytab(2.0.0.M9)
* org.apache.directory.server.kerberos.shared.replay(2.0.0.M9)
* org.apache.directory.server.kerberos.shared.store(2.0.0.M9)
* org.apache.directory.server.kerberos.shared.store.operations(2.0.0.M9)
* org.apache.directory.server.ldap(2.0.0.M9)
* org.apache.directory.server.ldap.handlers(2.0.0.M9)
* org.apache.directory.server.ldap.handlers.bind(2.0.0.M9)
* org.apache.directory.server.ldap.handlers.bind.cramMD5(2.0.0.M9)
* org.apache.directory.server.ldap.handlers.bind.digestMD5(2.0.0.M9)
* org.apache.directory.server.ldap.handlers.bind.gssapi(2.0.0.M9)
* org.apache.directory.server.ldap.handlers.bind.ntlm(2.0.0.M9)
* org.apache.directory.server.ldap.handlers.bind.plain(2.0.0.M9)
* org.apache.directory.server.ldap.handlers.controls(2.0.0.M9)
* org.apache.directory.server.ldap.handlers.extended(2.0.0.M9)
* org.apache.directory.server.ldap.handlers.request(2.0.0.M9)
* org.apache.directory.server.ldap.handlers.response(2.0.0.M9)
* org.apache.directory.server.ldap.handlers.ssl(2.0.0.M9)
* org.apache.directory.server.ldap.replication(2.0.0.M9)
* org.apache.directory.server.ldap.replication.consumer(2.0.0.M9)
* org.apache.directory.server.ldap.replication.provider(2.0.0.M9)
* org.apache.directory.server.ntp(2.0.0.M9)
* org.apache.directory.server.ntp.io(2.0.0.M9)
* org.apache.directory.server.ntp.messages(2.0.0.M9)
* org.apache.directory.server.ntp.protocol(2.0.0.M9)
* org.apache.directory.server.ntp.service(2.0.0.M9)
* org.apache.directory.server.protocol.shared(2.0.0.M9)
* org.apache.directory.server.protocol.shared.catalog(2.0.0.M9)
* org.apache.directory.server.protocol.shared.store(2.0.0.M9)
* org.apache.directory.server.protocol.shared.transport(2.0.0.M9)
* org.apache.directory.server.xdbm(2.0.0.M9)
* org.apache.directory.server.xdbm.impl.avl(2.0.0.M9)
* org.apache.directory.server.xdbm.search(2.0.0.M9)
* org.apache.directory.server.xdbm.search.cursor(2.0.0.M9)
* org.apache.directory.server.xdbm.search.evaluator(2.0.0.M9)
* org.apache.directory.server.xdbm.search.impl(2.0.0.M9)

## OSGi Dependencies
* __System Bundle - org.apache.felix.framework (4.0.3)__
	* javax.crypto
	* javax.crypto.spec
	* javax.naming
	* javax.naming.directory
	* javax.naming.event
	* javax.naming.ldap
	* javax.naming.spi
	* javax.net
	* javax.net.ssl
	* javax.security.auth
	* javax.security.auth.callback
	* javax.security.auth.kerberos
	* javax.security.auth.login
	* javax.security.auth.x500
	* javax.security.sasl
	* org.osgi.framework
* __Apache Commons IO Bundle - org.apache.commons.io (1.4)__
	* org.apache.commons.io
* __Commons Collections - org.apache.commons.collections (3.2.1)__
	* org.apache.commons.collections
	* org.apache.commons.collections.list
	* org.apache.commons.collections.map
* __Commons Lang - org.apache.commons.lang (2.6)__
	* org.apache.commons.lang
	* org.apache.commons.lang.builder
	* org.apache.commons.lang.exception
* __Commons Pool - org.apache.commons.pool (1.5.6)__
	* org.apache.commons.pool
	* org.apache.commons.pool.impl
* __Apache ServiceMix :: Bundles :: antlr - org.apache.servicemix.bundles.antlr (2.7.7.4)__
	* antlr
	* antlr.collections.impl
* __bcprov - bcprov (1.46)__
	* org.bouncycastle.jce.provider
	* org.bouncycastle.x509
* __Apache ServiceMix :: Bundles :: ehcache - org.apache.servicemix.bundles.ehcache (2.5.2.1)__
	* net.sf.ehcache
	* net.sf.ehcache.config
	* net.sf.ehcache.store
* __OPS4J Pax Logging - API - org.ops4j.pax.logging.pax-logging-api (1.7.0)__
	* org.slf4j
	* org.slf4j
	* org.slf4j
	* org.slf4j
* __Apache MINA Core - org.apache.mina.core (2.0.7)__
	* org.apache.mina.core.buffer
	* org.apache.mina.core.filterchain
	* org.apache.mina.core.future
	* org.apache.mina.core.service
	* org.apache.mina.core.session
	* org.apache.mina.core.write
	* org.apache.mina.filter.codec
	* org.apache.mina.filter.executor
	* org.apache.mina.filter.ssl
	* org.apache.mina.handler.chain
	* org.apache.mina.handler.demux
	* org.apache.mina.transport.socket
	* org.apache.mina.transport.socket.nio
	* org.apache.mina.util

## OSGi Embedded JARs

## Dependency Graph
![alt text](http://raw.github.com.everydayimmirror.in/liveSense/org.liveSense.framework.apacheds/master/osgidependencies.svg "")