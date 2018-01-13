<Type Name="IBlank" FullName="Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IBlank">
  <TypeSignature Language="C#" Value="public interface IBlank : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion&lt;Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.INewAppServicePlanWithGroup&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBlank implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion`1&lt;class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.INewAppServicePlanWithGroup&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IBlank" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBlank&#xA;Implements IDefinitionWithRegion(Of INewAppServicePlanWithGroup)" />
  <TypeSignature Language="F#" Value="type IBlank = interface&#xA;    interface IDefinitionWithRegion&lt;INewAppServicePlanWithGroup&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion&lt;Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.INewAppServicePlanWithGroup&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            関数アプリ定義の最初の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingAppServicePlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IExistingAppServicePlanWithGroup WithExistingAppServicePlan (Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan appServicePlan);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IExistingAppServicePlanWithGroup WithExistingAppServicePlan(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan appServicePlan) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IBlank.WithExistingAppServicePlan(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingAppServicePlan (appServicePlan As IAppServicePlan) As IExistingAppServicePlanWithGroup" />
      <MemberSignature Language="F#" Value="abstract member WithExistingAppServicePlan : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IExistingAppServicePlanWithGroup" Usage="iBlank.WithExistingAppServicePlan appServicePlan" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IExistingAppServicePlanWithGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan" />
      </Parameters>
      <Docs>
        <param name="appServicePlan">既存の app service プランです。</param>
        <summary>
            関数アプリの既存の app service プランを使用します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>