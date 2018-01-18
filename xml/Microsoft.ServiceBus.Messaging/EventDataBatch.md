<Type Name="EventDataBatch" FullName="Microsoft.ServiceBus.Messaging.EventDataBatch">
  <TypeSignature Language="C#" Value="public sealed class EventDataBatch : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventDataBatch extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventDataBatch" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventDataBatch&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type EventDataBatch = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="d6a5c-101">EventData オブジェクト SendBatch または SendBatchAsync 呼び出しをするためのバッチを作成するためのヘルパー クラス。</span><span class="sxs-lookup"><span data-stu-id="d6a5c-101">A helper class for creating a batch of EventData objects to be used for SendBatch or SendBatchAsync call.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventDataBatch (long maxSizeInBytes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 maxSizeInBytes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventDataBatch.#ctor(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxSizeInBytes As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventDataBatch : int64 -&gt; Microsoft.ServiceBus.Messaging.EventDataBatch" Usage="new Microsoft.ServiceBus.Messaging.EventDataBatch maxSizeInBytes" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxSizeInBytes" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="maxSizeInBytes"><span data-ttu-id="d6a5c-102">シリアル化されたバッチ メッセージの最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="d6a5c-102">The maximum size of the serialized batch message.</span></span></param>
        <summary>
            <span data-ttu-id="d6a5c-103">指定された最大サイズ (バイト単位) には、バッチを作成します。</span><span class="sxs-lookup"><span data-stu-id="d6a5c-103">Creates a batch with the specified maximum size in bytes.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="d6a5c-104">呼び出すことをお勧め<see cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateBatch" />または<see cref="M:Microsoft.ServiceBus.Messaging.EventHubSender.CreateBatch" />サービスとのネゴシエーションにメッセージの最大サイズを使用しているために、このクラスのインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="d6a5c-104">It is recommended to call <see cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateBatch" /> or <see cref="M:Microsoft.ServiceBus.Messaging.EventHubSender.CreateBatch" /> to create an instance of this class because it uses the maximum message size negotiated with the service.</span></span>
            <span data-ttu-id="d6a5c-105">アプリケーションでは、コンス トラクターを使用してバッチを作成するときは、サービスによって、maxSizeInBytes が許可されていることを確認します。</span><span class="sxs-lookup"><span data-stu-id="d6a5c-105">When the application creates a batch using the constructor, it is responsible to ensure the maxSizeInBytes is permitted by the service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventDataBatch.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.ServiceBus.Messaging.EventDataBatch.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d6a5c-106">バッチ内の現在のイベント数を取得します。</span><span class="sxs-lookup"><span data-stu-id="d6a5c-106">Gets the current event count in the batch.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventDataBatch.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="eventDataBatch.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d6a5c-107">このバッチに含まれる EventData オブジェクトを破棄します。</span><span class="sxs-lookup"><span data-stu-id="d6a5c-107">Disposes the EventData objects contained in this batch.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToEnumerable">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; ToEnumerable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; ToEnumerable() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventDataBatch.ToEnumerable" />
      <MemberSignature Language="VB.NET" Value="Public Function ToEnumerable () As IEnumerable(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.ToEnumerable : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" Usage="eventDataBatch.ToEnumerable " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d6a5c-108">バッチを SendBatch または SendBatchAsync メソッドによって受け付けられる EventData の IEnumerable オブジェクトに変換します。</span><span class="sxs-lookup"><span data-stu-id="d6a5c-108">Converts the batch to an IEnumerable of EventData objects that can be accepted by the SendBatch or SendBatchAsync method.</span></span></summary>
        <returns><span data-ttu-id="d6a5c-109">EventData の IEnumerable オブジェクトを返します。</span><span class="sxs-lookup"><span data-stu-id="d6a5c-109">Returns an IEnumerable of EventData objects.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryAdd">
      <MemberSignature Language="C#" Value="public bool TryAdd (Microsoft.ServiceBus.Messaging.EventData eventData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryAdd(class Microsoft.ServiceBus.Messaging.EventData eventData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventDataBatch.TryAdd(Microsoft.ServiceBus.Messaging.EventData)" />
      <MemberSignature Language="F#" Value="member this.TryAdd : Microsoft.ServiceBus.Messaging.EventData -&gt; bool" Usage="eventDataBatch.TryAdd eventData" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventData" Type="Microsoft.ServiceBus.Messaging.EventData" />
      </Parameters>
      <Docs>
        <param name="eventData"><span data-ttu-id="d6a5c-110">追加する <see cref="T:Microsoft.ServiceBus.Messaging.EventData" />。</span><span class="sxs-lookup"><span data-stu-id="d6a5c-110">The <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> to add.</span></span></param>
        <summary><span data-ttu-id="d6a5c-111">イベント データをバッチのサイズ制限によって許可されている場合のバッチに追加しようとしています。</span><span class="sxs-lookup"><span data-stu-id="d6a5c-111">Tries to add an event data to the batch if permitted by the batch's size limit.</span></span></summary>
        <returns><span data-ttu-id="d6a5c-112">バッチにイベント データが追加されているかどうかを示すブール値。</span><span class="sxs-lookup"><span data-stu-id="d6a5c-112">A boolean value indicating if the event data has been added to the batch or not.</span></span></returns>
        <remarks>
            <span data-ttu-id="d6a5c-113">このメソッドは、バッチ、EventData オブジェクトおよび EventData オブジェクトを追加するかどうかに指定された上限のサイズを確認します。</span><span class="sxs-lookup"><span data-stu-id="d6a5c-113">This method checks the sizes of the batch, the EventData object and the specified limit to determine if the EventData object can be added.</span></span> <span data-ttu-id="d6a5c-114">現在のバッチと EventData オブジェクトも他の検証は実行しません。</span><span class="sxs-lookup"><span data-stu-id="d6a5c-114">It does not perform other validations on the current batch and the EventData object.</span></span> <span data-ttu-id="d6a5c-115">バッチの EventData オブジェクトをバッチで送信できない場合に、アプリケーション可能性があります、送信呼び出しから例外を取得することができます。</span><span class="sxs-lookup"><span data-stu-id="d6a5c-115">It is possible that the application may get exceptions from the send call if the batched EventData objects cannot be sent in a batch.</span></span> <span data-ttu-id="d6a5c-116">たとえばが含まれている異なる<see cref="P:Microsoft.ServiceBus.Messaging.EventData.PartitionKey" />値。</span><span class="sxs-lookup"><span data-stu-id="d6a5c-116">For example, they contain different <see cref="P:Microsoft.ServiceBus.Messaging.EventData.PartitionKey" /> values.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="d6a5c-117">EventData が null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6a5c-117">Thrown when the EventData is null.</span></span></exception>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="d6a5c-118">バッチが既に破棄されている場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6a5c-118">Thrown when the batch is already disposed.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>