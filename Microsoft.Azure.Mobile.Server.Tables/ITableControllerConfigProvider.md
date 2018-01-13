<Type Name="ITableControllerConfigProvider" FullName="Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider">
  <TypeSignature Language="C#" Value="public interface ITableControllerConfigProvider" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITableControllerConfigProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITableControllerConfigProvider" />
  <TypeSignature Language="F#" Value="type ITableControllerConfigProvider = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="308f2-101">構成のカスタマイズを実行するための抽象化を提供<see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />コント ローラーを派生します。</span><span class="sxs-lookup"><span data-stu-id="308f2-101">Provides an abstraction for performing configuration customizations for <see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" /> derived controllers.</span></span> <span data-ttu-id="308f2-102">使用して登録できるは、実装、<see cref="T:System.Web.Http.HttpConfiguration" />です。</span><span class="sxs-lookup"><span data-stu-id="308f2-102">An implementation can be registered via the <see cref="T:System.Web.Http.HttpConfiguration" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Configure">
      <MemberSignature Language="C#" Value="public void Configure (System.Web.Http.Controllers.HttpControllerSettings controllerSettings, System.Web.Http.Controllers.HttpControllerDescriptor controllerDescriptor);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Configure(class System.Web.Http.Controllers.HttpControllerSettings controllerSettings, class System.Web.Http.Controllers.HttpControllerDescriptor controllerDescriptor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider.Configure(System.Web.Http.Controllers.HttpControllerSettings,System.Web.Http.Controllers.HttpControllerDescriptor)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Configure (controllerSettings As HttpControllerSettings, controllerDescriptor As HttpControllerDescriptor)" />
      <MemberSignature Language="F#" Value="abstract member Configure : System.Web.Http.Controllers.HttpControllerSettings * System.Web.Http.Controllers.HttpControllerDescriptor -&gt; unit" Usage="iTableControllerConfigProvider.Configure (controllerSettings, controllerDescriptor)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
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
        <param name="controllerSettings"><span data-ttu-id="308f2-103"><see cref="T:System.Web.Http.Controllers.HttpControllerSettings" />このコント ローラーの種類。</span><span class="sxs-lookup"><span data-stu-id="308f2-103">The <see cref="T:System.Web.Http.Controllers.HttpControllerSettings" /> for this controller type.</span></span></param>
        <param name="controllerDescriptor"><span data-ttu-id="308f2-104"><see cref="T:System.Web.Http.Controllers.HttpControllerDescriptor" />このコント ローラーの種類。</span><span class="sxs-lookup"><span data-stu-id="308f2-104">The <see cref="T:System.Web.Http.Controllers.HttpControllerDescriptor" /> for this controller type.</span></span></param>
        <summary>
            <span data-ttu-id="308f2-105">型のコント ローラーに固有の設定を構成<see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />です。</span><span class="sxs-lookup"><span data-stu-id="308f2-105">Configures the settings specific for controllers of type <see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>