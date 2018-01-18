<Type Name="ObjectsOperationsExtensions" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.ObjectsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ObjectsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ObjectsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.ObjectsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ObjectsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ObjectsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="711d4-101">ObjectsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="711d4-101">Extension methods for ObjectsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetCurrentUserAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt; GetCurrentUserAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IObjectsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt; GetCurrentUserAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IObjectsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ObjectsOperationsExtensions.GetCurrentUserAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IObjectsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCurrentUserAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IObjectsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ObjectsOperationsExtensions.GetCurrentUserAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ObjectsOperationsExtensions/&lt;GetCurrentUserAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IObjectsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="711d4-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="711d4-102">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="711d4-103">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="711d4-103">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="711d4-104">現在のログイン ユーザーの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="711d4-104">Gets the details for the currently logged-in user.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectsByObjectIdsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt; GetObjectsByObjectIdsAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IObjectsOperations operations, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GetObjectsParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt; GetObjectsByObjectIdsAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IObjectsOperations operations, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GetObjectsParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ObjectsOperationsExtensions.GetObjectsByObjectIdsAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IObjectsOperations,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GetObjectsParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetObjectsByObjectIdsAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IObjectsOperations * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GetObjectsParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ObjectsOperationsExtensions.GetObjectsByObjectIdsAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ObjectsOperationsExtensions/&lt;GetObjectsByObjectIdsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IObjectsOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GetObjectsParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectsByObjectIdsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt; GetObjectsByObjectIdsNextAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IObjectsOperations operations, string nextLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt; GetObjectsByObjectIdsNextAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IObjectsOperations operations, string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ObjectsOperationsExtensions.GetObjectsByObjectIdsNextAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IObjectsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetObjectsByObjectIdsNextAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IObjectsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ObjectsOperationsExtensions.GetObjectsByObjectIdsNextAsync (operations, nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ObjectsOperationsExtensions/&lt;GetObjectsByObjectIdsNextAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IObjectsOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>