<Type Name="DeploymentOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DeploymentOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DeploymentOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DeploymentOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DeploymentOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            DeploymentOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperations operations, string resourceGroupName, string deploymentName, string operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperations operations, string resourceGroupName, string deploymentName, string operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentOperationsExtensions.GetAsync (operations, resourceGroupName, deploymentName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentOperationsExtensions/&lt;GetAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="deploymentName">
            デプロイの名前。
            </param>
        <param name="operationId">
            操作 id です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            デプロイ操作の一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperations operations, string resourceGroupName, string deploymentName, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperations operations, string resourceGroupName, string deploymentName, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperations,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperations * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentOperationsExtensions.ListAsync (operations, resourceGroupName, deploymentName, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="deploymentName">
            デプロイの名前。
            </param>
        <param name="top">
            クエリ パラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            デプロイ操作の一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentOperationsExtensions/&lt;ListNextAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            デプロイ操作の一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>