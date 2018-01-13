<Type Name="HttpConfigurationExtensions" FullName="System.Web.Http.HttpConfigurationExtensions">
  <TypeSignature Language="C#" Value="public static class HttpConfigurationExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit HttpConfigurationExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Web.Http.HttpConfigurationExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module HttpConfigurationExtensions" />
  <TypeSignature Language="F#" Value="type HttpConfigurationExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.CrossDomain</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <see cref="T:System.Web.Http.HttpConfiguration" /> クラスの拡張メソッドを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetCachePolicyProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Mobile.Server.Cache.ICachePolicyProvider GetCachePolicyProvider (this System.Web.Http.HttpConfiguration config);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Mobile.Server.Cache.ICachePolicyProvider GetCachePolicyProvider(class System.Web.Http.HttpConfiguration config) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.HttpConfigurationExtensions.GetCachePolicyProvider(System.Web.Http.HttpConfiguration)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCachePolicyProvider (config As HttpConfiguration) As ICachePolicyProvider" />
      <MemberSignature Language="F#" Value="static member GetCachePolicyProvider : System.Web.Http.HttpConfiguration -&gt; Microsoft.Azure.Mobile.Server.Cache.ICachePolicyProvider" Usage="System.Web.Http.HttpConfigurationExtensions.GetCachePolicyProvider config" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Cache.ICachePolicyProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="System.Web.Http.HttpConfiguration" RefType="this" />
      </Parameters>
      <Docs>
        <param name="config">現在の <see cref="T:System.Web.Http.HttpConfiguration" /> です。</param>
        <summary>
            取得、<see cref="T:Microsoft.Azure.Mobile.Server.Cache.ICachePolicyProvider" />に現在登録されている<see cref="T:System.Web.Http.HttpConfiguration" />です。
            </summary>
        <returns>登録済みのインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCrossDomainOrigins">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;string&gt; GetCrossDomainOrigins (this System.Web.Http.HttpConfiguration config);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;string&gt; GetCrossDomainOrigins(class System.Web.Http.HttpConfiguration config) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.HttpConfigurationExtensions.GetCrossDomainOrigins(System.Web.Http.HttpConfiguration)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCrossDomainOrigins (config As HttpConfiguration) As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="static member GetCrossDomainOrigins : System.Web.Http.HttpConfiguration -&gt; seq&lt;string&gt;" Usage="System.Web.Http.HttpConfigurationExtensions.GetCrossDomainOrigins config" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.CrossDomain</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="System.Web.Http.HttpConfiguration" RefType="this" />
      </Parameters>
      <Docs>
        <param name="config">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMobileAppConfiguration">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration GetMobileAppConfiguration (this System.Web.Http.HttpConfiguration config);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration GetMobileAppConfiguration(class System.Web.Http.HttpConfiguration config) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.HttpConfigurationExtensions.GetMobileAppConfiguration(System.Web.Http.HttpConfiguration)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetMobileAppConfiguration (config As HttpConfiguration) As MobileAppConfiguration" />
      <MemberSignature Language="F#" Value="static member GetMobileAppConfiguration : System.Web.Http.HttpConfiguration -&gt; Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" Usage="System.Web.Http.HttpConfigurationExtensions.GetMobileAppConfiguration config" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="System.Web.Http.HttpConfiguration" RefType="this" />
      </Parameters>
      <Docs>
        <param name="config">現在の <see cref="T:System.Web.Http.HttpConfiguration" /> です。</param>
        <summary>
            取得、<see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" />に現在登録されている<see cref="T:System.Web.Http.HttpConfiguration" />です。
            </summary>
        <returns>登録済みのインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMobileAppControllerConfigProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider GetMobileAppControllerConfigProvider (this System.Web.Http.HttpConfiguration config);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider GetMobileAppControllerConfigProvider(class System.Web.Http.HttpConfiguration config) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.HttpConfigurationExtensions.GetMobileAppControllerConfigProvider(System.Web.Http.HttpConfiguration)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetMobileAppControllerConfigProvider (config As HttpConfiguration) As IMobileAppControllerConfigProvider" />
      <MemberSignature Language="F#" Value="static member GetMobileAppControllerConfigProvider : System.Web.Http.HttpConfiguration -&gt; Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider" Usage="System.Web.Http.HttpConfigurationExtensions.GetMobileAppControllerConfigProvider config" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="System.Web.Http.HttpConfiguration" RefType="this" />
      </Parameters>
      <Docs>
        <param name="config">現在の <see cref="T:System.Web.Http.HttpConfiguration" /> です。</param>
        <summary>
            取得、<see cref="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider" />に現在登録されている<see cref="T:System.Web.Http.HttpConfiguration" />です。
            </summary>
        <returns>登録済みのインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMobileAppSettingsProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider GetMobileAppSettingsProvider (this System.Web.Http.HttpConfiguration config);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider GetMobileAppSettingsProvider(class System.Web.Http.HttpConfiguration config) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.HttpConfigurationExtensions.GetMobileAppSettingsProvider(System.Web.Http.HttpConfiguration)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetMobileAppSettingsProvider (config As HttpConfiguration) As IMobileAppSettingsProvider" />
      <MemberSignature Language="F#" Value="static member GetMobileAppSettingsProvider : System.Web.Http.HttpConfiguration -&gt; Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider" Usage="System.Web.Http.HttpConfigurationExtensions.GetMobileAppSettingsProvider config" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="System.Web.Http.HttpConfiguration" RefType="this" />
      </Parameters>
      <Docs>
        <param name="config">現在の <see cref="T:System.Web.Http.HttpConfiguration" /> です。</param>
        <summary>
            取得、<see cref="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider" />に現在登録されている<see cref="T:System.Web.Http.HttpConfiguration" />です。
            </summary>
        <returns>登録済みのインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPushClient">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Mobile.Server.Notifications.PushClient GetPushClient (this System.Web.Http.HttpConfiguration config);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Mobile.Server.Notifications.PushClient GetPushClient(class System.Web.Http.HttpConfiguration config) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.HttpConfigurationExtensions.GetPushClient(System.Web.Http.HttpConfiguration)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetPushClient (config As HttpConfiguration) As PushClient" />
      <MemberSignature Language="F#" Value="static member GetPushClient : System.Web.Http.HttpConfiguration -&gt; Microsoft.Azure.Mobile.Server.Notifications.PushClient" Usage="System.Web.Http.HttpConfigurationExtensions.GetPushClient config" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Notifications.PushClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="System.Web.Http.HttpConfiguration" RefType="this" />
      </Parameters>
      <Docs>
        <param name="config">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetCachePolicyProvider">
      <MemberSignature Language="C#" Value="public static void SetCachePolicyProvider (this System.Web.Http.HttpConfiguration config, Microsoft.Azure.Mobile.Server.Cache.ICachePolicyProvider provider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetCachePolicyProvider(class System.Web.Http.HttpConfiguration config, class Microsoft.Azure.Mobile.Server.Cache.ICachePolicyProvider provider) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.HttpConfigurationExtensions.SetCachePolicyProvider(System.Web.Http.HttpConfiguration,Microsoft.Azure.Mobile.Server.Cache.ICachePolicyProvider)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SetCachePolicyProvider (config As HttpConfiguration, provider As ICachePolicyProvider)" />
      <MemberSignature Language="F#" Value="static member SetCachePolicyProvider : System.Web.Http.HttpConfiguration * Microsoft.Azure.Mobile.Server.Cache.ICachePolicyProvider -&gt; unit" Usage="System.Web.Http.HttpConfigurationExtensions.SetCachePolicyProvider (config, provider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="System.Web.Http.HttpConfiguration" RefType="this" />
        <Parameter Name="provider" Type="Microsoft.Azure.Mobile.Server.Cache.ICachePolicyProvider" />
      </Parameters>
      <Docs>
        <param name="config">現在の <see cref="T:System.Web.Http.HttpConfiguration" /> です。</param>
        <param name="provider">登録するインスタンス。</param>
        <summary>
            登録、 <see cref="T:Microsoft.Azure.Mobile.Server.Cache.ICachePolicyProvider" /> 、現在の<see cref="T:System.Web.Http.HttpConfiguration" />します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetCrossDomainOrigins">
      <MemberSignature Language="C#" Value="public static void SetCrossDomainOrigins (this System.Web.Http.HttpConfiguration config, System.Collections.Generic.IEnumerable&lt;string&gt; crossDomainOrigins);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetCrossDomainOrigins(class System.Web.Http.HttpConfiguration config, class System.Collections.Generic.IEnumerable`1&lt;string&gt; crossDomainOrigins) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.HttpConfigurationExtensions.SetCrossDomainOrigins(System.Web.Http.HttpConfiguration,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SetCrossDomainOrigins (config As HttpConfiguration, crossDomainOrigins As IEnumerable(Of String))" />
      <MemberSignature Language="F#" Value="static member SetCrossDomainOrigins : System.Web.Http.HttpConfiguration * seq&lt;string&gt; -&gt; unit" Usage="System.Web.Http.HttpConfigurationExtensions.SetCrossDomainOrigins (config, crossDomainOrigins)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.CrossDomain</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="System.Web.Http.HttpConfiguration" RefType="this" />
        <Parameter Name="crossDomainOrigins" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="config">To be added.</param>
        <param name="crossDomainOrigins">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMobileAppConfiguration">
      <MemberSignature Language="C#" Value="public static void SetMobileAppConfiguration (this System.Web.Http.HttpConfiguration config, Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration options);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetMobileAppConfiguration(class System.Web.Http.HttpConfiguration config, class Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration options) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.HttpConfigurationExtensions.SetMobileAppConfiguration(System.Web.Http.HttpConfiguration,Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SetMobileAppConfiguration (config As HttpConfiguration, options As MobileAppConfiguration)" />
      <MemberSignature Language="F#" Value="static member SetMobileAppConfiguration : System.Web.Http.HttpConfiguration * Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration -&gt; unit" Usage="System.Web.Http.HttpConfigurationExtensions.SetMobileAppConfiguration (config, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="System.Web.Http.HttpConfiguration" RefType="this" />
        <Parameter Name="options" Type="Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" />
      </Parameters>
      <Docs>
        <param name="config">現在の <see cref="T:System.Web.Http.HttpConfiguration" /> です。</param>
        <param name="options">登録するインスタンス。</param>
        <summary>
            登録、 <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" /> 、現在の<see cref="T:System.Web.Http.HttpConfiguration" />します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMobileAppControllerConfigProvider">
      <MemberSignature Language="C#" Value="public static void SetMobileAppControllerConfigProvider (this System.Web.Http.HttpConfiguration config, Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider configProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetMobileAppControllerConfigProvider(class System.Web.Http.HttpConfiguration config, class Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider configProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.HttpConfigurationExtensions.SetMobileAppControllerConfigProvider(System.Web.Http.HttpConfiguration,Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SetMobileAppControllerConfigProvider (config As HttpConfiguration, configProvider As IMobileAppControllerConfigProvider)" />
      <MemberSignature Language="F#" Value="static member SetMobileAppControllerConfigProvider : System.Web.Http.HttpConfiguration * Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider -&gt; unit" Usage="System.Web.Http.HttpConfigurationExtensions.SetMobileAppControllerConfigProvider (config, configProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="System.Web.Http.HttpConfiguration" RefType="this" />
        <Parameter Name="configProvider" Type="Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider" />
      </Parameters>
      <Docs>
        <param name="config">現在の <see cref="T:System.Web.Http.HttpConfiguration" /> です。</param>
        <param name="configProvider">登録するインスタンス。</param>
        <summary>
            登録、 <see cref="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider" /> 、現在の<see cref="T:System.Web.Http.HttpConfiguration" />します。
            登録されているクラスは、基本コント ローラーの設定を使用して、提供、<see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppControllerAttribute" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMobileAppSettingsProvider">
      <MemberSignature Language="C#" Value="public static void SetMobileAppSettingsProvider (this System.Web.Http.HttpConfiguration config, Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider provider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetMobileAppSettingsProvider(class System.Web.Http.HttpConfiguration config, class Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider provider) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.HttpConfigurationExtensions.SetMobileAppSettingsProvider(System.Web.Http.HttpConfiguration,Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SetMobileAppSettingsProvider (config As HttpConfiguration, provider As IMobileAppSettingsProvider)" />
      <MemberSignature Language="F#" Value="static member SetMobileAppSettingsProvider : System.Web.Http.HttpConfiguration * Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider -&gt; unit" Usage="System.Web.Http.HttpConfigurationExtensions.SetMobileAppSettingsProvider (config, provider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="System.Web.Http.HttpConfiguration" RefType="this" />
        <Parameter Name="provider" Type="Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider" />
      </Parameters>
      <Docs>
        <param name="config">現在の <see cref="T:System.Web.Http.HttpConfiguration" /> です。</param>
        <param name="provider">登録するインスタンス。</param>
        <summary>
            登録、 <see cref="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider" /> 、現在の<see cref="T:System.Web.Http.HttpConfiguration" />します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPushClient">
      <MemberSignature Language="C#" Value="public static void SetPushClient (this System.Web.Http.HttpConfiguration config, Microsoft.Azure.Mobile.Server.Notifications.PushClient client);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetPushClient(class System.Web.Http.HttpConfiguration config, class Microsoft.Azure.Mobile.Server.Notifications.PushClient client) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.HttpConfigurationExtensions.SetPushClient(System.Web.Http.HttpConfiguration,Microsoft.Azure.Mobile.Server.Notifications.PushClient)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SetPushClient (config As HttpConfiguration, client As PushClient)" />
      <MemberSignature Language="F#" Value="static member SetPushClient : System.Web.Http.HttpConfiguration * Microsoft.Azure.Mobile.Server.Notifications.PushClient -&gt; unit" Usage="System.Web.Http.HttpConfigurationExtensions.SetPushClient (config, client)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="System.Web.Http.HttpConfiguration" RefType="this" />
        <Parameter Name="client" Type="Microsoft.Azure.Mobile.Server.Notifications.PushClient" />
      </Parameters>
      <Docs>
        <param name="config">To be added.</param>
        <param name="client">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>