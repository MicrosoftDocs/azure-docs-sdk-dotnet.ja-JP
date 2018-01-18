<Type Name="QueueMessage" FullName="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage">
  <TypeSignature Language="C#" Value="public class QueueMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit QueueMessage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage" />
  <TypeSignature Language="VB.NET" Value="Public Class QueueMessage" />
  <TypeSignature Language="F#" Value="type QueueMessage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="02b65-101">キューから取得したメッセージを表します。</span><span class="sxs-lookup"><span data-stu-id="02b65-101">Represents a message retrieved from a queue.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DequeueCount">
      <MemberSignature Language="C#" Value="public int DequeueCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DequeueCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.DequeueCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DequeueCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DequeueCount : int" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.DequeueCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02b65-102">このメッセージがデキューされた回数を取得します。</span><span class="sxs-lookup"><span data-stu-id="02b65-102">Gets the number of times this message has been dequeued.</span></span>
            </summary>
        <value><span data-ttu-id="02b65-103">デキューの回数。</span><span class="sxs-lookup"><span data-stu-id="02b65-103">The dequeue count.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; ExpirationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02b65-104">メッセージの有効期限を取得します。</span><span class="sxs-lookup"><span data-stu-id="02b65-104">Gets the message expiration time.</span></span>
            </summary>
        <value><span data-ttu-id="02b65-105">メッセージの期限。</span><span class="sxs-lookup"><span data-stu-id="02b65-105">The message expiration time.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02b65-106">メッセージ ID を取得します</span><span class="sxs-lookup"><span data-stu-id="02b65-106">Gets the message ID.</span></span>
            </summary>
        <value><span data-ttu-id="02b65-107">メッセージ ID。</span><span class="sxs-lookup"><span data-stu-id="02b65-107">The message ID.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; InsertionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; InsertionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.InsertionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InsertionTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.InsertionTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.InsertionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02b65-108">メッセージがキューに追加された時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="02b65-108">Gets the time the message was added to the queue.</span></span>
            </summary>
        <value><span data-ttu-id="02b65-109">メッセージの挿入時間。</span><span class="sxs-lookup"><span data-stu-id="02b65-109">The message insertion time.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextVisibleTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; NextVisibleTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; NextVisibleTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.NextVisibleTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextVisibleTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.NextVisibleTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.NextVisibleTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02b65-110">表示されるメッセージは次の時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="02b65-110">Gets the time the message is next visible.</span></span>
            </summary>
        <value><span data-ttu-id="02b65-111">メッセージが表示される次の時間。</span><span class="sxs-lookup"><span data-stu-id="02b65-111">The time the message is next visible.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PopReceipt">
      <MemberSignature Language="C#" Value="public string PopReceipt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PopReceipt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.PopReceipt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PopReceipt As String" />
      <MemberSignature Language="F#" Value="member this.PopReceipt : string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.PopReceipt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02b65-112">メッセージの popreceipt を取得します。</span><span class="sxs-lookup"><span data-stu-id="02b65-112">Gets the pop receipt for the message.</span></span>
            </summary>
        <value><span data-ttu-id="02b65-113">メッセージのポップ受信。</span><span class="sxs-lookup"><span data-stu-id="02b65-113">The message's pop receipt.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Text">
      <MemberSignature Language="C#" Value="public string Text { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Text" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.Text" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Text As String" />
      <MemberSignature Language="F#" Value="member this.Text : string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.Text" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02b65-114">メッセージのテキストを取得します。</span><span class="sxs-lookup"><span data-stu-id="02b65-114">Gets the text of the message.</span></span>
            </summary>
        <value><span data-ttu-id="02b65-115">メッセージ テキストです。</span><span class="sxs-lookup"><span data-stu-id="02b65-115">The message text.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>