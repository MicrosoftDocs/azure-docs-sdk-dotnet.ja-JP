<Type Name="NotifyStateManagerRebuildEventArgs" FullName="Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerRebuildEventArgs">
  <TypeSignature Language="C#" Value="public class NotifyStateManagerRebuildEventArgs : Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NotifyStateManagerRebuildEventArgs extends Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerRebuildEventArgs" />
  <TypeSignature Language="VB.NET" Value="Public Class NotifyStateManagerRebuildEventArgs&#xA;Inherits NotifyStateManagerChangedEventArgs" />
  <TypeSignature Language="F#" Value="type NotifyStateManagerRebuildEventArgs = class&#xA;    inherit NotifyStateManagerChangedEventArgs" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3cfab-101">再構築による StateManagerChanged イベントのデータを提供します。</span><span class="sxs-lookup"><span data-stu-id="3cfab-101">Provides data for the StateManagerChanged event caused by a rebuild.</span></span>
            <span data-ttu-id="3cfab-102">一般的な回復、復元、およびコピーの終了時に呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="3cfab-102">Commonly called during recovery, restore and end of copy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotifyStateManagerRebuildEventArgs (Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt; reliableStates);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;class Microsoft.ServiceFabric.Data.IReliableState&gt; reliableStates) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerRebuildEventArgs.#ctor(Microsoft.ServiceFabric.Data.IAsyncEnumerable{Microsoft.ServiceFabric.Data.IReliableState})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (reliableStates As IAsyncEnumerable(Of IReliableState))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerRebuildEventArgs : Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt; -&gt; Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerRebuildEventArgs" Usage="new Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerRebuildEventArgs reliableStates" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="reliableStates" Type="Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;" />
      </Parameters>
      <Docs>
        <param name="reliableStates">
          <span data-ttu-id="3cfab-103"><cref name="IAsyncEnumerable" />再構築後にすべて ReliableState の</span><span class="sxs-lookup"><span data-stu-id="3cfab-103"><cref name="IAsyncEnumerable" /> of all the ReliableState after the rebuild.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3cfab-104">新しいインスタンスを初期化します<cref name="NotifyStateManagerChangedEventArgs" /></span><span class="sxs-lookup"><span data-stu-id="3cfab-104">Initializes a new instance of the <cref name="NotifyStateManagerChangedEventArgs" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReliableStates">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt; ReliableStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;class Microsoft.ServiceFabric.Data.IReliableState&gt; ReliableStates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerRebuildEventArgs.ReliableStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReliableStates As IAsyncEnumerable(Of IReliableState)" />
      <MemberSignature Language="F#" Value="member this.ReliableStates : Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerRebuildEventArgs.ReliableStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cfab-105">これで、状態マネージャー内のすべての新しい状態プロバイダーの列挙可能です。</span><span class="sxs-lookup"><span data-stu-id="3cfab-105">Enumerable of all the new state providers now in the State Manager.</span></span>
            </summary>
        <value>
            <span data-ttu-id="3cfab-106">新しいセットを含む列挙可能な非同期<cref name="IReliableState" />s。</span><span class="sxs-lookup"><span data-stu-id="3cfab-106">Asynchronous enumerable that contains the new set of <cref name="IReliableState" />s.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>