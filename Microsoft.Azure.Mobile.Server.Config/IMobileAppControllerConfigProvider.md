<Type Name="IMobileAppControllerConfigProvider" FullName="Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider">
  <TypeSignature Language="C#" Value="public interface IMobileAppControllerConfigProvider" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileAppControllerConfigProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileAppControllerConfigProvider" />
  <TypeSignature Language="F#" Value="type IMobileAppControllerConfigProvider = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            提供されたコント ローラーの構成のカスタマイズを実行するための抽象、<see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppControllerAttribute" />です。
            使用して登録できるは、実装、<see cref="T:System.Web.Http.HttpConfiguration" />です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Configure">
      <MemberSignature Language="C#" Value="public void Configure (System.Web.Http.Controllers.HttpControllerSettings controllerSettings, System.Web.Http.Controllers.HttpControllerDescriptor controllerDescriptor);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Configure(class System.Web.Http.Controllers.HttpControllerSettings controllerSettings, class System.Web.Http.Controllers.HttpControllerDescriptor controllerDescriptor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider.Configure(System.Web.Http.Controllers.HttpControllerSettings,System.Web.Http.Controllers.HttpControllerDescriptor)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Configure (controllerSettings As HttpControllerSettings, controllerDescriptor As HttpControllerDescriptor)" />
      <MemberSignature Language="F#" Value="abstract member Configure : System.Web.Http.Controllers.HttpControllerSettings * System.Web.Http.Controllers.HttpControllerDescriptor -&gt; unit" Usage="iMobileAppControllerConfigProvider.Configure (controllerSettings, controllerDescriptor)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="controllerSettings" Type="System.Web.Http.Controllers.HttpControllerSettings" />
        <Parameter Name="controllerDescriptor" Type="System.Web.Http.Controllers.HttpControllerDescriptor" />
      </Parameters>
      <Docs>
        <param name="controllerSettings"><see cref="T:System.Web.Http.Controllers.HttpControllerSettings" />このコント ローラーの種類。</param>
        <param name="controllerDescriptor"><see cref="T:System.Web.Http.Controllers.HttpControllerDescriptor" />このコント ローラーの種類。</param>
        <summary>
            使用してコント ローラーに固有の設定を構成<see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppControllerAttribute" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>