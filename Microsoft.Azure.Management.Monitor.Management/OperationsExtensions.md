<Type Name="OperationsExtensions" FullName="Microsoft.Azure.Management.Monitor.Management.OperationsExtensions">
  <TypeSignature Language="C#" Value="public static class OperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit OperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.OperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module OperationsExtensions" />
  <TypeSignature Language="F#" Value="type OperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b9c92-101">操作の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="b9c92-101">Extension methods for Operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Monitor.Management.Models.OperationListResult List (this Microsoft.Azure.Management.Monitor.Management.IOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Monitor.Management.Models.OperationListResult List(class Microsoft.Azure.Management.Monitor.Management.IOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.OperationsExtensions.List(Microsoft.Azure.Management.Monitor.Management.IOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IOperations) As OperationListResult" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Monitor.Management.IOperations -&gt; Microsoft.Azure.Management.Monitor.Management.Models.OperationListResult" Usage="Microsoft.Azure.Management.Monitor.Management.OperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.OperationListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b9c92-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b9c92-102">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9c92-103">Microsoft.insights にプロバイダーから使用可能な操作のすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="b9c92-103">Lists all of the available operations from Microsoft.Insights provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.OperationListResult&gt; ListAsync (this Microsoft.Azure.Management.Monitor.Management.IOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.OperationListResult&gt; ListAsync(class Microsoft.Azure.Management.Monitor.Management.IOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.OperationsExtensions.ListAsync(Microsoft.Azure.Management.Monitor.Management.IOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Monitor.Management.IOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.OperationListResult&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.OperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.OperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.OperationListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b9c92-104">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b9c92-104">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b9c92-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b9c92-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9c92-106">Microsoft.insights にプロバイダーから使用可能な操作のすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="b9c92-106">Lists all of the available operations from Microsoft.Insights provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>