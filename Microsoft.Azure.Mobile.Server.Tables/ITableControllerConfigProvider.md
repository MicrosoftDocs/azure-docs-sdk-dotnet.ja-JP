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
            構成のカスタマイズを実行するための抽象化を提供<see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />コント ローラーを派生します。 使用して登録できるは、実装、<see cref="T:System.Web.Http.HttpConfiguration" />です。
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
        <param name="controllerSettings"><see cref="T:System.Web.Http.Controllers.HttpControllerSettings" />このコント ローラーの種類。</param>
        <param name="controllerDescriptor"><see cref="T:System.Web.Http.Controllers.HttpControllerDescriptor" />このコント ローラーの種類。</param>
        <summary>
            型のコント ローラーに固有の設定を構成<see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>