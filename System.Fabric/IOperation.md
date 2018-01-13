<Type Name="IOperation" FullName="System.Fabric.IOperation">
  <TypeSignature Language="C#" Value="public interface IOperation" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IOperation" />
  <TypeSignature Language="VB.NET" Value="Public Interface IOperation" />
  <TypeSignature Language="F#" Value="type IOperation = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>状態の複製物作成会社から取得されるデータをについて説明します。 </para>
    </summary>
    <remarks>
      <para>
        <see cref="T:System.Fabric.IOperation" />セカンダリ レプリカに配信される状態の変化を説明する基本インターフェイスです。 </para>
      <para>
                含まれている、<see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />とシーケンス番号およびその他の情報を識別します。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Acknowledge">
      <MemberSignature Language="C#" Value="public void Acknowledge ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Acknowledge() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IOperation.Acknowledge" />
      <MemberSignature Language="VB.NET" Value="Public Sub Acknowledge ()" />
      <MemberSignature Language="F#" Value="abstract member Acknowledge : unit -&gt; unit" Usage="iOperation.Acknowledge " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>この操作が、セカンダリ レプリカに正常に適用されたことを確認します。  </para>
        </summary>
        <remarks>
          <para>取得するときに、サービスはこのメソッドを呼び出す必要があります、<see cref="T:System.Fabric.IOperation" />複製物作成会社と正常にローカル ストアに適用します。
            永続化されたサービスでは、このメソッドを呼び出すことが必須ため、<see cref="T:System.Fabric.FabricReplicator" />を実装するその他のオブジェクトを解放しない<see cref="T:System.Fabric.IOperation" />です。 揮発性サービスでは、レプリケーターに暗黙的に承認されると operations 値の設定でそれ以外の場合は構成しない限り、受信したとき<see cref="P:System.Fabric.ReplicatorSettings.RequireServiceAck" />true に設定します。
            プライマリ レプリカを受け取る前に、レプリカのクォーラム操作を確認する必要があります、<see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />操作完了の応答。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AtomicGroupId">
      <MemberSignature Language="C#" Value="public long AtomicGroupId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 AtomicGroupId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IOperation.AtomicGroupId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AtomicGroupId As Long" />
      <MemberSignature Language="F#" Value="member this.AtomicGroupId : int64" Usage="System.Fabric.IOperation.AtomicGroupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>このオブジェクトを実装している場合、分割不可能なグループを識別<see cref="T:System.Fabric.IOperation" />アトミック グループの一部です。 分割不可能なグループはサービスがサービス グループの一部であるときにのみ使用できます。</para>
        </summary>
        <value>
          <para><see cref="T:System.Int64" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public System.Fabric.OperationData Data { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.OperationData Data" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IOperation.Data" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Data As OperationData" />
      <MemberSignature Language="F#" Value="member this.Data : System.Fabric.OperationData" Usage="System.Fabric.IOperation.Data" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.OperationData</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得、<see cref="T:System.Fabric.OperationData" />プライマリ レプリカによって提供されます。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.OperationData" /> を返します。</para>
        </value>
        <remarks>
          <para />
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationType">
      <MemberSignature Language="C#" Value="public System.Fabric.OperationType OperationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.OperationType OperationType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IOperation.OperationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationType As OperationType" />
      <MemberSignature Language="F#" Value="member this.OperationType : System.Fabric.OperationType" Usage="System.Fabric.IOperation.OperationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.OperationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>この操作の種類を取得します。 </para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.OperationType" /> を返します。</para>
        </value>
        <remarks>
          <para><see cref="T:System.Fabric.OperationType" />操作の種類を示します。 "Normal"操作は、コピーまたはレプリケーション ストリームの一部としてグループ化のサービスによって送信されるこれらの操作です。 その他の種類の操作は、サービス グループに固有の管理操作を表します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IOperation.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="System.Fabric.IOperation.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>この操作のシーケンス番号を取得します。 </para>
        </summary>
        <value>
          <para><see cref="T:System.Int64" /> を返します。</para>
        </value>
        <remarks>
          <para>
                シーケンス番号がの一部として提供される、<see cref="P:System.Fabric.IOperation.SequenceNumber" /></para>
          <para>
                レプリケーションのストリームから受信した操作 (<see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" />) からは、プライマリ レプリカを受信すると、同じシーケンス番号は<see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />メソッドです。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>