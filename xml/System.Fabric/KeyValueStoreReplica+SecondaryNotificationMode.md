<Type Name="KeyValueStoreReplica+SecondaryNotificationMode" FullName="System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode">
  <TypeSignature Language="C#" Value="public enum KeyValueStoreReplica.SecondaryNotificationMode" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed KeyValueStoreReplica/SecondaryNotificationMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum KeyValueStoreReplica.SecondaryNotificationMode" />
  <TypeSignature Language="F#" Value="type KeyValueStoreReplica.SecondaryNotificationMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="1cae9-101">動作を指定<see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" />と<see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" />セカンダリ ロールのレプリカです。</span><span class="sxs-lookup"><span data-stu-id="1cae9-101">Specifies the behavior of <see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" /> and <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> for replicas in the secondary role.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BlockSecondaryAck">
      <MemberSignature Language="C#" Value="BlockSecondaryAck" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.KeyValueStoreReplica/SecondaryNotificationMode BlockSecondaryAck = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.BlockSecondaryAck" />
      <MemberSignature Language="VB.NET" Value="BlockSecondaryAck" />
      <MemberSignature Language="F#" Value="BlockSecondaryAck = 3" Usage="System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.BlockSecondaryAck" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1cae9-102">セカンダリ レプリカに適用またはされませんまでレプリケーション操作の確認、<see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" />コールバック メソッドを返します。</span><span class="sxs-lookup"><span data-stu-id="1cae9-102">The secondary replica will not apply or acknowledge replication operations until the <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> callback method returns.</span></span> <span data-ttu-id="1cae9-103">操作とは限りません ack 応答をされているレプリカのクォーラム、コールバックが呼び出された時にします。</span><span class="sxs-lookup"><span data-stu-id="1cae9-103">Operations are not guaranteed to have been acked by a quorum of replicas at the time the callback is invoked.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.KeyValueStoreReplica/SecondaryNotificationMode Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1cae9-104">無効な通知モードの場合です。</span><span class="sxs-lookup"><span data-stu-id="1cae9-104">An invalid secondary notification mode.</span></span> <span data-ttu-id="1cae9-105">将来使用するために予約されています。</span><span class="sxs-lookup"><span data-stu-id="1cae9-105">Reserved for future use.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="NonBlockingQuorumAcked">
      <MemberSignature Language="C#" Value="NonBlockingQuorumAcked" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.KeyValueStoreReplica/SecondaryNotificationMode NonBlockingQuorumAcked = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.NonBlockingQuorumAcked" />
      <MemberSignature Language="VB.NET" Value="NonBlockingQuorumAcked" />
      <MemberSignature Language="F#" Value="NonBlockingQuorumAcked = 2" Usage="System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.NonBlockingQuorumAcked" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1cae9-106">セカンダリ レプリカは既に適用してレプリケーション操作を確認して可能性があるときに、<see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" />コールバック メソッドが呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="1cae9-106">The secondary replica may have already applied and acknowledged replication operations when the <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> callback method is invoked.</span></span> <span data-ttu-id="1cae9-107">操作は、コールバックが呼び出された時点で、ack 応答があったに、レプリカのクォーラムが保証されます。</span><span class="sxs-lookup"><span data-stu-id="1cae9-107">Operations are guaranteed to have been acked by a quorum of replicas by the time the callback is invoked.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.KeyValueStoreReplica/SecondaryNotificationMode None = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 1" Usage="System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1cae9-108">セカンダリの通知が無効になります。</span><span class="sxs-lookup"><span data-stu-id="1cae9-108">Secondary notifications are disabled.</span></span> <span data-ttu-id="1cae9-109">どちらも<see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" />も<see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" />が呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="1cae9-109">Neither <see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" /> nor <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> will be invoked.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>