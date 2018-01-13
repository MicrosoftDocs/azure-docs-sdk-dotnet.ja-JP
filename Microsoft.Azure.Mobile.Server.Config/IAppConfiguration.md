<Type Name="IAppConfiguration" FullName="Microsoft.Azure.Mobile.Server.Config.IAppConfiguration">
  <TypeSignature Language="C#" Value="public interface IAppConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAppConfiguration" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Config.IAppConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAppConfiguration" />
  <TypeSignature Language="F#" Value="type IAppConfiguration = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            変更するためのメカニズムを提供、<see cref="T:System.Web.Http.HttpConfiguration" />モバイル アプリのです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplyTo">
      <MemberSignature Language="C#" Value="public void ApplyTo (System.Web.Http.HttpConfiguration config);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ApplyTo(class System.Web.Http.HttpConfiguration config) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.IAppConfiguration.ApplyTo(System.Web.Http.HttpConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ApplyTo (config As HttpConfiguration)" />
      <MemberSignature Language="F#" Value="abstract member ApplyTo : System.Web.Http.HttpConfiguration -&gt; unit" Usage="iAppConfiguration.ApplyTo config" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="System.Web.Http.HttpConfiguration" />
      </Parameters>
      <Docs>
        <param name="config"><see cref="T:System.Web.Http.HttpConfiguration" />の各呼び出しに渡される<see cref="M:Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider.Initialize(System.Web.Http.HttpConfiguration)" />です。</param>
        <summary>
            呼び出し<see cref="M:Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider.Initialize(System.Web.Http.HttpConfiguration)" />をすべて登録<see cref="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterConfigProvider">
      <MemberSignature Language="C#" Value="public void RegisterConfigProvider (Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider provider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterConfigProvider(class Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider provider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.IAppConfiguration.RegisterConfigProvider(Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterConfigProvider (provider As IMobileAppExtensionConfigProvider)" />
      <MemberSignature Language="F#" Value="abstract member RegisterConfigProvider : Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider -&gt; unit" Usage="iAppConfiguration.RegisterConfigProvider provider" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="provider" Type="Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider" />
      </Parameters>
      <Docs>
        <param name="provider">登録する <see cref="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider" />。</param>
        <summary>
            追加、<see cref="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider" />によって呼び出されるプロバイダーの一覧に、<see cref="M:Microsoft.Azure.Mobile.Server.Config.AppConfiguration.ApplyTo(System.Web.Http.HttpConfiguration)" />メソッドです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>