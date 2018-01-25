<Type Name="FabricClient+InfrastructureServiceClient" FullName="System.Fabric.FabricClient+InfrastructureServiceClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.InfrastructureServiceClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/InfrastructureServiceClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.InfrastructureServiceClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.InfrastructureServiceClient" />
  <TypeSignature Language="F#" Value="type FabricClient.InfrastructureServiceClient = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="832d3-101">インフラストラクチャに固有の操作を実行するためのメソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="832d3-101">Provides methods for performing infrastructure-specific operations.</span></span></para>
      <para><span data-ttu-id="832d3-102">このクラスは、Service Fabric プラットフォームをサポートしていますコードから直接呼び出されるものではありません。</span><span class="sxs-lookup"><span data-stu-id="832d3-102">This class supports the Service Fabric platform; it is not meant to be called directly from your code.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="832d3-103">このクライアントを使用する前に、InfrastructureService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="832d3-103">The InfrastructureService must be enabled before this client can be used.</span></span> <span data-ttu-id="832d3-104">InfrastructureService は、いくつかのインフラストラクチャでのみサポートされます。</span><span class="sxs-lookup"><span data-stu-id="832d3-104">The InfrastructureService is only supported on some infrastructures.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="InvokeInfrastructureCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; InvokeInfrastructureCommandAsync (Uri serviceName, string command);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; InvokeInfrastructureCommandAsync(class System.Uri serviceName, string command) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.InfrastructureServiceClient.InvokeInfrastructureCommandAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function InvokeInfrastructureCommandAsync (serviceName As Uri, command As String) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.InvokeInfrastructureCommandAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="infrastructureServiceClient.InvokeInfrastructureCommandAsync (serviceName, command)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="command" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="832d3-105">対象のインフラストラクチャのサービス インスタンスの名前。</span><span class="sxs-lookup"><span data-stu-id="832d3-105">The name of the target infrastructure service instance.</span></span></para>
        </param>
        <param name="command">
          <para><span data-ttu-id="832d3-106">呼び出されるコマンドのテキスト。</span><span class="sxs-lookup"><span data-stu-id="832d3-106">The text of the command to be invoked.</span></span>  <span data-ttu-id="832d3-107">コマンドのコンテンツは、インフラストラクチャに固有です。</span><span class="sxs-lookup"><span data-stu-id="832d3-107">The content of the command is infrastructure-specific.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="832d3-108">指定されたインフラストラクチャのサービス インスタンスで管理コマンドを非同期的に呼び出します。</span><span class="sxs-lookup"><span data-stu-id="832d3-108">Asynchronously invokes an administrative command on the given infrastructure service instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="832d3-109">インフラストラクチャ サービスからの応答。</span><span class="sxs-lookup"><span data-stu-id="832d3-109">The response from the infrastructure service.</span></span> <span data-ttu-id="832d3-110">応答の形式は、JSON 文字列です。</span><span class="sxs-lookup"><span data-stu-id="832d3-110">The response format is a JSON string.</span></span> <span data-ttu-id="832d3-111">応答の内容は、どのコマンドが発行されましたによって異なります。</span><span class="sxs-lookup"><span data-stu-id="832d3-111">The contents of the response depend on which command was issued.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeInfrastructureCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; InvokeInfrastructureCommandAsync (Uri serviceName, string command, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; InvokeInfrastructureCommandAsync(class System.Uri serviceName, string command, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.InfrastructureServiceClient.InvokeInfrastructureCommandAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeInfrastructureCommandAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="infrastructureServiceClient.InvokeInfrastructureCommandAsync (serviceName, command, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="command" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="832d3-112">対象のインフラストラクチャのサービス インスタンスの名前。</span><span class="sxs-lookup"><span data-stu-id="832d3-112">The name of the target infrastructure service instance.</span></span></para>
        </param>
        <param name="command">
          <para><span data-ttu-id="832d3-113">呼び出されるコマンドのテキスト。</span><span class="sxs-lookup"><span data-stu-id="832d3-113">The text of the command to be invoked.</span></span>  <span data-ttu-id="832d3-114">コマンドのコンテンツは、インフラストラクチャに固有です。</span><span class="sxs-lookup"><span data-stu-id="832d3-114">The content of the command is infrastructure-specific.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="832d3-115">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="832d3-115">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="832d3-116">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="832d3-116">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="832d3-117">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="832d3-117">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="832d3-118">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="832d3-118">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="832d3-119">インフラストラクチャ サービスで管理コマンドを非同期的に呼び出します。</span><span class="sxs-lookup"><span data-stu-id="832d3-119">Asynchronously invokes an administrative command on an infrastructure service.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="832d3-120">インフラストラクチャ サービスからの応答。</span><span class="sxs-lookup"><span data-stu-id="832d3-120">The response from the infrastructure service.</span></span> <span data-ttu-id="832d3-121">応答の形式は、JSON 文字列です。</span><span class="sxs-lookup"><span data-stu-id="832d3-121">The response format is a JSON string.</span></span> <span data-ttu-id="832d3-122">応答の内容は、どのコマンドが発行されましたによって異なります。</span><span class="sxs-lookup"><span data-stu-id="832d3-122">The contents of the response depend on which command was issued.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeInfrastructureQueryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; InvokeInfrastructureQueryAsync (Uri serviceName, string command);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; InvokeInfrastructureQueryAsync(class System.Uri serviceName, string command) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.InfrastructureServiceClient.InvokeInfrastructureQueryAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function InvokeInfrastructureQueryAsync (serviceName As Uri, command As String) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.InvokeInfrastructureQueryAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="infrastructureServiceClient.InvokeInfrastructureQueryAsync (serviceName, command)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="command" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="832d3-123">対象のインフラストラクチャのサービス インスタンスの名前。</span><span class="sxs-lookup"><span data-stu-id="832d3-123">The name of the target infrastructure service instance.</span></span></para>
        </param>
        <param name="command">
          <para><span data-ttu-id="832d3-124">呼び出されるコマンドのテキスト。</span><span class="sxs-lookup"><span data-stu-id="832d3-124">The text of the command to be invoked.</span></span>  <span data-ttu-id="832d3-125">コマンドのコンテンツは、インフラストラクチャに固有です。</span><span class="sxs-lookup"><span data-stu-id="832d3-125">The content of the command is infrastructure-specific.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="832d3-126">指定されたインフラストラクチャのサービス インスタンスでの読み取り専用クエリを非同期的に呼び出します。</span><span class="sxs-lookup"><span data-stu-id="832d3-126">Asynchronously invokes a read-only query on the given infrastructure service instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="832d3-127">インフラストラクチャ サービスからの応答。</span><span class="sxs-lookup"><span data-stu-id="832d3-127">The response from the infrastructure service.</span></span> <span data-ttu-id="832d3-128">応答の形式は、JSON 文字列です。</span><span class="sxs-lookup"><span data-stu-id="832d3-128">The response format is a JSON string.</span></span> <span data-ttu-id="832d3-129">応答の内容は、どのコマンドが発行されましたによって異なります。</span><span class="sxs-lookup"><span data-stu-id="832d3-129">The contents of the response depend on which command was issued.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeInfrastructureQueryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; InvokeInfrastructureQueryAsync (Uri serviceName, string command, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; InvokeInfrastructureQueryAsync(class System.Uri serviceName, string command, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.InfrastructureServiceClient.InvokeInfrastructureQueryAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeInfrastructureQueryAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="infrastructureServiceClient.InvokeInfrastructureQueryAsync (serviceName, command, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="command" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="832d3-130">対象のインフラストラクチャのサービス インスタンスの名前。</span><span class="sxs-lookup"><span data-stu-id="832d3-130">The name of the target infrastructure service instance.</span></span></para>
        </param>
        <param name="command">
          <para><span data-ttu-id="832d3-131">呼び出されるコマンドのテキスト。</span><span class="sxs-lookup"><span data-stu-id="832d3-131">The text of the command to be invoked.</span></span>  <span data-ttu-id="832d3-132">コマンドのコンテンツは、インフラストラクチャに固有です。</span><span class="sxs-lookup"><span data-stu-id="832d3-132">The content of the command is infrastructure-specific.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="832d3-133">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="832d3-133">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="832d3-134">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="832d3-134">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="832d3-135">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="832d3-135">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="832d3-136">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="832d3-136">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="832d3-137">指定されたインフラストラクチャのサービス インスタンスでの読み取り専用クエリを非同期的に呼び出します。</span><span class="sxs-lookup"><span data-stu-id="832d3-137">Asynchronously invokes a read-only query on the given infrastructure service instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="832d3-138">インフラストラクチャ サービスからの応答。</span><span class="sxs-lookup"><span data-stu-id="832d3-138">The response from the infrastructure service.</span></span> <span data-ttu-id="832d3-139">応答の形式は、JSON 文字列です。</span><span class="sxs-lookup"><span data-stu-id="832d3-139">The response format is a JSON string.</span></span> <span data-ttu-id="832d3-140">応答の内容は、どのコマンドが発行されましたによって異なります。</span><span class="sxs-lookup"><span data-stu-id="832d3-140">The contents of the response depend on which command was issued.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>