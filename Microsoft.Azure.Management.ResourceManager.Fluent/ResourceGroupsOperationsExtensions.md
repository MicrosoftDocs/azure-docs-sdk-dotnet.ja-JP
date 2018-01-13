<Type Name="ResourceGroupsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ResourceGroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ResourceGroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ResourceGroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ResourceGroupsOperationsExtensions = class" />
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
            ResourceGroupsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            削除するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; CheckExistenceAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; CheckExistenceAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.CheckExistenceAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckExistenceAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.CheckExistenceAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;CheckExistenceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            確認するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループが存在するかどうかを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            作成または更新するリソース グループの名前。
            </param>
        <param name="parameters">
            作成または更新リソース グループのサービス操作に渡されるパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.DeleteAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            削除するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportTemplateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupExportResultInner&gt; ExportTemplateAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupExportResultInner&gt; ExportTemplateAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ExportTemplateAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExportTemplateAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupExportResultInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ExportTemplateAsync (operations, resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;ExportTemplateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupExportResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            作成または更新するリソース グループの名前。
            </param>
        <param name="parameters">
            エクスポート テンプレート リソース グループの操作に渡されるパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            テンプレートとして指定されたリソース グループをキャプチャします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.GetAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;GetAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupFilterInner&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupFilterInner&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupFilterInner},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupFilterInner&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ListAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupFilterInner&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループのコレクションを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;ListNextAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
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
            リソース グループのコレクションを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt; ListResourcesAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceFilterInner&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt; ListResourcesAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceFilterInner&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ListResourcesAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceFilterInner},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListResourcesAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceFilterInner&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ListResourcesAsync (operations, resourceGroupName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;ListResourcesAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceFilterInner&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            クエリ パラメーター。 Null が渡される場合は、すべてのリソース グループを返します。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべてのサブスクリプションの下にあるリソースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourcesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt; ListResourcesNextAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt; ListResourcesNextAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ListResourcesNextAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListResourcesNextAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ListResourcesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;ListResourcesNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
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
            すべてのサブスクリプションの下にあるリソースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt; PatchAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt; PatchAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.PatchAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.PatchAsync (operations, resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;PatchAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            作成または更新するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="parameters">
            更新状態リソース グループのサービス操作に渡されるパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループは、グループ アドレスに対する単純な PATCH 操作で更新できます。 要求の形式と同じではリソース グループを作成するためのフィールドが指定されていない場合、現在の値が引き継がれます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>