<Type Name="OperationsExtensions" FullName="Microsoft.Azure.Management.IotHub.OperationsExtensions">
  <TypeSignature Language="C#" Value="public static class OperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit OperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.OperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module OperationsExtensions" />
  <TypeSignature Language="F#" Value="type OperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4c8be-101">操作の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="4c8be-101">Extension methods for Operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.Operation&gt; List (this Microsoft.Azure.Management.IotHub.IOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.Operation&gt; List(class Microsoft.Azure.Management.IotHub.IOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.OperationsExtensions.List(Microsoft.Azure.Management.IotHub.IOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IOperations) As IPage(Of Operation)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.IotHub.IOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.Operation&gt;" Usage="Microsoft.Azure.Management.IotHub.OperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.Operation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c8be-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4c8be-102">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c8be-103">すべての使用できる IoT Hub の REST API 操作の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="4c8be-103">Lists all of the available IoT Hub REST API operations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.Operation&gt;&gt; ListAsync (this Microsoft.Azure.Management.IotHub.IOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.Operation&gt;&gt; ListAsync(class Microsoft.Azure.Management.IotHub.IOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.OperationsExtensions.ListAsync(Microsoft.Azure.Management.IotHub.IOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.IotHub.IOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.Operation&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.OperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.OperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.Operation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c8be-104">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4c8be-104">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c8be-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c8be-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c8be-106">すべての使用できる IoT Hub の REST API 操作の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="4c8be-106">Lists all of the available IoT Hub REST API operations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.Operation&gt; ListNext (this Microsoft.Azure.Management.IotHub.IOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.Operation&gt; ListNext(class Microsoft.Azure.Management.IotHub.IOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.OperationsExtensions.ListNext(Microsoft.Azure.Management.IotHub.IOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IOperations, nextPageLink As String) As IPage(Of Operation)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.IotHub.IOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.Operation&gt;" Usage="Microsoft.Azure.Management.IotHub.OperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.Operation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c8be-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4c8be-107">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4c8be-108">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="4c8be-108">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c8be-109">すべての使用できる IoT Hub の REST API 操作の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="4c8be-109">Lists all of the available IoT Hub REST API operations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.Operation&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.IotHub.IOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.Operation&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.IotHub.IOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.OperationsExtensions.ListNextAsync(Microsoft.Azure.Management.IotHub.IOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.IotHub.IOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.Operation&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.OperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.OperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.Operation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c8be-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4c8be-110">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4c8be-111">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="4c8be-111">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c8be-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c8be-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c8be-113">すべての使用できる IoT Hub の REST API 操作の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="4c8be-113">Lists all of the available IoT Hub REST API operations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>