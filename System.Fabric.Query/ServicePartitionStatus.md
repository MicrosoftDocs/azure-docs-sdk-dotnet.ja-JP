<Type Name="ServicePartitionStatus" FullName="System.Fabric.Query.ServicePartitionStatus">
  <TypeSignature Language="C#" Value="public enum ServicePartitionStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServicePartitionStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ServicePartitionStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServicePartitionStatus" />
  <TypeSignature Language="F#" Value="type ServicePartitionStatus = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>サービス パーティションの状態を指定します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Deleting">
      <MemberSignature Language="C#" Value="Deleting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServicePartitionStatus Deleting = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServicePartitionStatus.Deleting" />
      <MemberSignature Language="VB.NET" Value="Deleting" />
      <MemberSignature Language="F#" Value="Deleting = 5" Usage="System.Fabric.Query.ServicePartitionStatus.Deleting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServicePartitionStatus</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
          <para>パーティションが削除されます。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="InQuorumLoss">
      <MemberSignature Language="C#" Value="InQuorumLoss" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServicePartitionStatus InQuorumLoss = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServicePartitionStatus.InQuorumLoss" />
      <MemberSignature Language="VB.NET" Value="InQuorumLoss" />
      <MemberSignature Language="F#" Value="InQuorumLoss = 3" Usage="System.Fabric.Query.ServicePartitionStatus.InQuorumLoss" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServicePartitionStatus</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>パーティションはクォーラム損失です。 つまり、クォーラムに参加しているレプリカの MinReplicaSetSize 数未満です。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServicePartitionStatus Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServicePartitionStatus.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Query.ServicePartitionStatus.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServicePartitionStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="NotReady">
      <MemberSignature Language="C#" Value="NotReady" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServicePartitionStatus NotReady = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServicePartitionStatus.NotReady" />
      <MemberSignature Language="VB.NET" Value="NotReady" />
      <MemberSignature Language="F#" Value="NotReady = 2" Usage="System.Fabric.Query.ServicePartitionStatus.NotReady" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServicePartitionStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>パーティション準備ができていません。 他の状態のいずれにも該当する場合に返されます。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Ready">
      <MemberSignature Language="C#" Value="Ready" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServicePartitionStatus Ready = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServicePartitionStatus.Ready" />
      <MemberSignature Language="VB.NET" Value="Ready" />
      <MemberSignature Language="F#" Value="Ready = 1" Usage="System.Fabric.Query.ServicePartitionStatus.Ready" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServicePartitionStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>
                パーティション準備ができました。</para>
          <para>
                ステートレスなサービスが 1 つのレプリカを</para>
          <para>
                ステートフル サービスの準備がレプリカの数より大きいまたは等しい、<see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" /></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Reconfiguring">
      <MemberSignature Language="C#" Value="Reconfiguring" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServicePartitionStatus Reconfiguring = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServicePartitionStatus.Reconfiguring" />
      <MemberSignature Language="VB.NET" Value="Reconfiguring" />
      <MemberSignature Language="F#" Value="Reconfiguring = 4" Usage="System.Fabric.Query.ServicePartitionStatus.Reconfiguring" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServicePartitionStatus</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>パーティションは再構成を実行中です。</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>