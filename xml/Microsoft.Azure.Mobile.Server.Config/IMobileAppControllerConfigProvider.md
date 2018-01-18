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
            <span data-ttu-id="fbe94-101">提供されたコント ローラーの構成のカスタマイズを実行するための抽象、<see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppControllerAttribute" />です。</span><span class="sxs-lookup"><span data-stu-id="fbe94-101">Provides an abstraction for performing configuration customizations for controllers with the <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppControllerAttribute" />.</span></span>
            <span data-ttu-id="fbe94-102">使用して登録できるは、実装、<see cref="T:System.Web.Http.HttpConfiguration" />です。</span><span class="sxs-lookup"><span data-stu-id="fbe94-102">An implementation can be registered via the <see cref="T:System.Web.Http.HttpConfiguration" />.</span></span>
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
        <param name="controllerSettings"><span data-ttu-id="fbe94-103"><see cref="T:System.Web.Http.Controllers.HttpControllerSettings" />このコント ローラーの種類。</span><span class="sxs-lookup"><span data-stu-id="fbe94-103">The <see cref="T:System.Web.Http.Controllers.HttpControllerSettings" /> for this controller type.</span></span></param>
        <param name="controllerDescriptor"><span data-ttu-id="fbe94-104"><see cref="T:System.Web.Http.Controllers.HttpControllerDescriptor" />このコント ローラーの種類。</span><span class="sxs-lookup"><span data-stu-id="fbe94-104">The <see cref="T:System.Web.Http.Controllers.HttpControllerDescriptor" /> for this controller type.</span></span></param>
        <summary>
            <span data-ttu-id="fbe94-105">使用してコント ローラーに固有の設定を構成<see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppControllerAttribute" />です。</span><span class="sxs-lookup"><span data-stu-id="fbe94-105">Configures the settings specific for controllers using <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppControllerAttribute" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>