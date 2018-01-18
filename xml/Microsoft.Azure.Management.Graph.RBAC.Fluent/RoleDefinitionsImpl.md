<Type Name="RoleDefinitionsImpl" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl">
  <TypeSignature Language="C#" Value="public class RoleDefinitionsImpl : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ReadableWrappers&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition,Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionImpl,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.RoleDefinitionInner&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitionsOperations&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RoleDefinitionsImpl extends Microsoft.Azure.Management.ResourceManager.Fluent.Core.ReadableWrappers`3&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition, class Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionImpl, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.RoleDefinitionInner&gt; implements class Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitionsOperations&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl" />
  <TypeSignature Language="VB.NET" Value="Public Class RoleDefinitionsImpl&#xA;Inherits ReadableWrappers(Of IRoleDefinition, RoleDefinitionImpl, RoleDefinitionInner)&#xA;Implements IBeta, IHasInner(Of IRoleDefinitionsOperations), IHasManager(Of GraphRbacManager), IRoleDefinitions, ISupportsGettingById(Of IRoleDefinition)" />
  <TypeSignature Language="F#" Value="type RoleDefinitionsImpl = class&#xA;    inherit ReadableWrappers&lt;IRoleDefinition, RoleDefinitionImpl, RoleDefinitionInner&gt;&#xA;    interface IRoleDefinitions&#xA;    interface IBeta&#xA;    interface ISupportsGettingById&lt;IRoleDefinition&gt;&#xA;    interface IHasManager&lt;GraphRbacManager&gt;&#xA;    interface IHasInner&lt;IRoleDefinitionsOperations&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ReadableWrappers&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition,Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionImpl,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.RoleDefinitionInner&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="!1">Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionImpl</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="!2">Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.RoleDefinitionInner</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitionsOperations&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetById">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionImpl GetById (string objectId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionImpl GetById(string objectId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.GetById(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetById (objectId As String) As RoleDefinitionImpl" />
      <MemberSignature Language="F#" Value="member this.GetById : string -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionImpl" Usage="roleDefinitionsImpl.GetById objectId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionImpl</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="objectId">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByIdAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt; GetByIdAsync (string id, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt; GetByIdAsync(string id, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.GetByIdAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetByIdAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;&#xA;override this.GetByIdAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;" Usage="roleDefinitionsImpl.GetByIdAsync (id, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById`1.GetByIdAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl/&lt;GetByIdAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByScope">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionImpl GetByScope (string scope, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionImpl GetByScope(string scope, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.GetByScope(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetByScope (scope As String, name As String) As RoleDefinitionImpl" />
      <MemberSignature Language="F#" Value="member this.GetByScope : string * string -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionImpl" Usage="roleDefinitionsImpl.GetByScope (scope, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionImpl</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scope">To be added.</param>
        <param name="name">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByScopeAndRoleName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionImpl GetByScopeAndRoleName (string scope, string roleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionImpl GetByScopeAndRoleName(string scope, string roleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.GetByScopeAndRoleName(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetByScopeAndRoleName (scope As String, roleName As String) As RoleDefinitionImpl" />
      <MemberSignature Language="F#" Value="member this.GetByScopeAndRoleName : string * string -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionImpl" Usage="roleDefinitionsImpl.GetByScopeAndRoleName (scope, roleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionImpl</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="roleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scope">To be added.</param>
        <param name="roleName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByScopeAndRoleNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt; GetByScopeAndRoleNameAsync (string scope, string roleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt; GetByScopeAndRoleNameAsync(string scope, string roleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.GetByScopeAndRoleNameAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetByScopeAndRoleNameAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;" Usage="roleDefinitionsImpl.GetByScopeAndRoleNameAsync (scope, roleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.GetByScopeAndRoleNameAsync(System.String,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl/&lt;GetByScopeAndRoleNameAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="roleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">To be added.</param>
        <param name="roleName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByScopeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt; GetByScopeAsync (string scope, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt; GetByScopeAsync(string scope, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.GetByScopeAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetByScopeAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;" Usage="roleDefinitionsImpl.GetByScopeAsync (scope, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.GetByScopeAsync(System.String,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl/&lt;GetByScopeAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">To be added.</param>
        <param name="name">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Inner">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitionsOperations Inner { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitionsOperations Inner" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.Inner" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Inner As IRoleDefinitionsOperations" />
      <MemberSignature Language="F#" Value="member this.Inner : Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitionsOperations" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.Inner" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1.Inner</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitionsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByScope">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt; ListByScope (string scope);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt; ListByScope(string scope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.ListByScope(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListByScope (scope As String) As IEnumerable(Of IRoleDefinition)" />
      <MemberSignature Language="F#" Value="member this.ListByScope : string -&gt; seq&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;" Usage="roleDefinitionsImpl.ListByScope scope" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.ListByScope(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scope">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByScopeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;&gt; ListByScopeAsync (string scope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;&gt; ListByScopeAsync(string scope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.ListByScopeAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ListByScopeAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;&gt;" Usage="roleDefinitionsImpl.ListByScopeAsync (scope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl/&lt;ListByScopeAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Manager">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager Manager ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager Manager() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.Manager" />
      <MemberSignature Language="VB.NET" Value="Public Function Manager () As GraphRbacManager" />
      <MemberSignature Language="F#" Value="member this.Manager : unit -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager" Usage="roleDefinitionsImpl.Manager " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.GetByScope">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition IRoleDefinitions.GetByScope (string scope, string name);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.GetByScope(string scope, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.Microsoft#Azure#Management#Graph#RBAC#Fluent#IRoleDefinitions#GetByScope(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Function GetByScope (scope As String, name As String) As IRoleDefinition Implements IRoleDefinitions.GetByScope" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.GetByScope(System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scope">To be added.</param>
        <param name="name">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.GetByScopeAndRoleName">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition IRoleDefinitions.GetByScopeAndRoleName (string scope, string roleName);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.GetByScopeAndRoleName(string scope, string roleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.Microsoft#Azure#Management#Graph#RBAC#Fluent#IRoleDefinitions#GetByScopeAndRoleName(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Function GetByScopeAndRoleName (scope As String, roleName As String) As IRoleDefinition Implements IRoleDefinitions.GetByScopeAndRoleName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.GetByScopeAndRoleName(System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="roleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scope">To be added.</param>
        <param name="roleName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.GetByScopeAndRoleNameAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt; IRoleDefinitions.GetByScopeAndRoleNameAsync (string scope, string roleName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.GetByScopeAndRoleNameAsync(string scope, string roleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.Microsoft#Azure#Management#Graph#RBAC#Fluent#IRoleDefinitions#GetByScopeAndRoleNameAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.GetByScopeAndRoleNameAsync(System.String,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl/&lt;Microsoft-Azure-Management-Graph-RBAC-Fluent-IRoleDefinitions-GetByScopeAndRoleNameAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="roleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">To be added.</param>
        <param name="roleName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.GetByScopeAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt; IRoleDefinitions.GetByScopeAsync (string scope, string name, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.GetByScopeAsync(string scope, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.Microsoft#Azure#Management#Graph#RBAC#Fluent#IRoleDefinitions#GetByScopeAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.GetByScopeAsync(System.String,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl/&lt;Microsoft-Azure-Management-Graph-RBAC-Fluent-IRoleDefinitions-GetByScopeAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">To be added.</param>
        <param name="name">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.ListByScope">
      <MemberSignature Language="C#" Value="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt; IRoleDefinitions.ListByScope (string scope);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.ListByScope(string scope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.Microsoft#Azure#Management#Graph#RBAC#Fluent#IRoleDefinitions#ListByScope(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function ListByScope (scope As String) As IEnumerable(Of IRoleDefinition) Implements IRoleDefinitions.ListByScope" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.ListByScope(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scope">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.ListByScopeAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt; IRoleDefinitions.ListByScopeAsync (string scope, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.ListByScopeAsync(string scope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.Microsoft#Azure#Management#Graph#RBAC#Fluent#IRoleDefinitions#ListByScopeAsync(System.String,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinitions.ListByScopeAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl/&lt;Microsoft-Azure-Management-Graph-RBAC-Fluent-IRoleDefinitions-ListByScopeAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;.GetById">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition ISupportsGettingById&lt;IRoleDefinition&gt;.GetById (string id);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition&gt;.GetById(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.Microsoft#Azure#Management#ResourceManager#Fluent#Core#CollectionActions#ISupportsGettingById&lt;Microsoft#Azure#Management#Graph#RBAC#Fluent#IRoleDefinition&gt;#GetById(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function GetById (id As String) As IRoleDefinition Implements ISupportsGettingById(Of IRoleDefinition).GetById" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById`1.GetById(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager&gt;.Manager">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager&gt;.Manager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager&gt;.Manager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.Microsoft#Azure#Management#ResourceManager#Fluent#Core#IHasManager&lt;Microsoft#Azure#Management#Graph#RBAC#Fluent#GraphRbacManager&gt;#Manager" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property Manager As GraphRbacManager Implements IHasManager(Of GraphRbacManager).Manager" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager&gt;.Manager" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1.Manager</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WrapModel">
      <MemberSignature Language="C#" Value="protected override Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition WrapModel (Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.RoleDefinitionInner roleDefinitionInner);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition WrapModel(class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.RoleDefinitionInner roleDefinitionInner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.RoleDefinitionsImpl.WrapModel(Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.RoleDefinitionInner)" />
      <MemberSignature Language="F#" Value="override this.WrapModel : Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.RoleDefinitionInner -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition" Usage="roleDefinitionsImpl.WrapModel roleDefinitionInner" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.IRoleDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="roleDefinitionInner" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.RoleDefinitionInner" />
      </Parameters>
      <Docs>
        <param name="roleDefinitionInner">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>