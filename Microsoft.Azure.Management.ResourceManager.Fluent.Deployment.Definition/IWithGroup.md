<Type Name="IWithGroup" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithGroup">
  <TypeSignature Language="C#" Value="public interface IWithGroup : Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithExistingResourceGroup&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithGroup implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithExistingResourceGroup`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithGroup" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithGroup&#xA;Implements IWithExistingResourceGroup(Of IWithTemplate)" />
  <TypeSignature Language="F#" Value="type IWithGroup = interface&#xA;    interface IWithExistingResourceGroup&lt;IWithTemplate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithExistingResourceGroup&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            リソース グループを指定するを許可する展開の定義。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewResourceGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate WithNewResourceGroup (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt; groupDefinition);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate WithNewResourceGroup(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt; groupDefinition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithGroup.WithNewResourceGroup(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewResourceGroup (groupDefinition As ICreatable(Of IResourceGroup)) As IWithTemplate" />
      <MemberSignature Language="F#" Value="abstract member WithNewResourceGroup : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate" Usage="iWithGroup.WithNewResourceGroup groupDefinition" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupDefinition" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;" />
      </Parameters>
      <Docs>
        <param name="groupDefinition">groupDefinition 作成可能な新しいリソース グループの定義</param>
        <summary>
            指定された定義に基づき、リソースを格納する新しいリソース グループを作成します。
            </summary>
        <returns>展開の定義の次のステージ</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithNewResourceGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate WithNewResourceGroup (string name, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate WithNewResourceGroup(string name, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithGroup.WithNewResourceGroup(System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region)" />
      <MemberSignature Language="F#" Value="abstract member WithNewResourceGroup : string * Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate" Usage="iWithGroup.WithNewResourceGroup (name, region)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="region" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" />
      </Parameters>
      <Docs>
        <param name="name">新しいグループを名前します。</param>
        <param name="region">領域内のリソース グループを作成する領域</param>
        <summary>
            展開を格納する新しいリソース グループを作成します。
            </summary>
        <returns>展開の定義の次のステージ</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>