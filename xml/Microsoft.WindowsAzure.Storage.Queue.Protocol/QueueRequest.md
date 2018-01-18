<Type Name="QueueRequest" FullName="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueRequest">
  <TypeSignature Language="C#" Value="public static class QueueRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit QueueRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class QueueRequest" />
  <TypeSignature Language="F#" Value="type QueueRequest = class" />
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
            <span data-ttu-id="f0abb-101">キュー サービスに対する要求を構築するためのヘルパー メソッドのセットを提供します。</span><span class="sxs-lookup"><span data-stu-id="f0abb-101">Provides a set of helper methods for constructing a request against the Queue service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WriteMessageContent">
      <MemberSignature Language="C#" Value="public static void WriteMessageContent (string messageContent, System.IO.Stream outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void WriteMessageContent(string messageContent, class System.IO.Stream outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueRequest.WriteMessageContent(System.String,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub WriteMessageContent (messageContent As String, outputStream As Stream)" />
      <MemberSignature Language="F#" Value="static member WriteMessageContent : string * System.IO.Stream -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueRequest.WriteMessageContent (messageContent, outputStream)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageContent" Type="System.String" />
        <Parameter Name="outputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="messageContent"><span data-ttu-id="f0abb-102">メッセージの本文。</span><span class="sxs-lookup"><span data-stu-id="f0abb-102">The message body.</span></span></param>
        <param name="outputStream"><span data-ttu-id="f0abb-103">出力ストリーム。</span><span class="sxs-lookup"><span data-stu-id="f0abb-103">An output stream.</span></span></param>
        <summary>
            <span data-ttu-id="f0abb-104">メッセージを XML 形式で指定したストリームに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="f0abb-104">Writes a message to the specified stream in XML format.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteSharedAccessIdentifiers">
      <MemberSignature Language="C#" Value="public static void WriteSharedAccessIdentifiers (Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies sharedAccessPolicies, System.IO.Stream outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void WriteSharedAccessIdentifiers(class Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies sharedAccessPolicies, class System.IO.Stream outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueRequest.WriteSharedAccessIdentifiers(Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub WriteSharedAccessIdentifiers (sharedAccessPolicies As SharedAccessQueuePolicies, outputStream As Stream)" />
      <MemberSignature Language="F#" Value="static member WriteSharedAccessIdentifiers : Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies * System.IO.Stream -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueRequest.WriteSharedAccessIdentifiers (sharedAccessPolicies, outputStream)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sharedAccessPolicies" Type="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies" />
        <Parameter Name="outputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="sharedAccessPolicies"><span data-ttu-id="f0abb-105">共有アクセス ポリシーのコレクション。</span><span class="sxs-lookup"><span data-stu-id="f0abb-105">A collection of shared access policies.</span></span></param>
        <param name="outputStream"><span data-ttu-id="f0abb-106">出力ストリーム。</span><span class="sxs-lookup"><span data-stu-id="f0abb-106">An output stream.</span></span></param>
        <summary>
            <span data-ttu-id="f0abb-107">共有アクセス ポリシーのコレクションを XML 形式で指定したストリームに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="f0abb-107">Writes a collection of shared access policies to the specified stream in XML format.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>