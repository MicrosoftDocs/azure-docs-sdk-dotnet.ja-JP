<Type Name="OperationsExtensions" FullName="Microsoft.Azure.Management.ContainerInstance.OperationsExtensions">
  <TypeSignature Language="C#" Value="public static class OperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit OperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.OperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module OperationsExtensions" />
  <TypeSignature Language="F#" Value="type OperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3f648-101">操作の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="3f648-101">Extension methods for Operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerInstance.Models.OperationListResult List (this Microsoft.Azure.Management.ContainerInstance.IOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerInstance.Models.OperationListResult List(class Microsoft.Azure.Management.ContainerInstance.IOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.OperationsExtensions.List(Microsoft.Azure.Management.ContainerInstance.IOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IOperations) As OperationListResult" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ContainerInstance.IOperations -&gt; Microsoft.Azure.Management.ContainerInstance.Models.OperationListResult" Usage="Microsoft.Azure.Management.ContainerInstance.OperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerInstance.Models.OperationListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f648-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3f648-102">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f648-103">Azure のコンテナー インスタンスのサービスに対する操作を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="3f648-103">List the operations for Azure Container Instance service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerInstance.Models.OperationListResult&gt; ListAsync (this Microsoft.Azure.Management.ContainerInstance.IOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.OperationListResult&gt; ListAsync(class Microsoft.Azure.Management.ContainerInstance.IOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.OperationsExtensions.ListAsync(Microsoft.Azure.Management.ContainerInstance.IOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ContainerInstance.IOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerInstance.Models.OperationListResult&gt;" Usage="Microsoft.Azure.Management.ContainerInstance.OperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerInstance.OperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerInstance.Models.OperationListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f648-104">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3f648-104">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f648-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3f648-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f648-106">Azure のコンテナー インスタンスのサービスに対する操作を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="3f648-106">List the operations for Azure Container Instance service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>