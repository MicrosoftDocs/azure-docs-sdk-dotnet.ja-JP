<Type Name="ResolvedServicePartition" FullName="System.Fabric.ResolvedServicePartition">
  <TypeSignature Language="C#" Value="public sealed class ResolvedServicePartition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ResolvedServicePartition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ResolvedServicePartition" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ResolvedServicePartition" />
  <TypeSignature Language="F#" Value="type ResolvedServicePartition = class" />
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
      <para>
            解決されたサービスと一連のパーティションにアクセスするために使用するエンドポイントのパーティションに関する情報が含まれています。</para>
    </summary>
    <remarks>
      <para>
            解決済みのサービス パーティションを取得する呼び出しの結果<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />およびその他のオーバー ロードします。
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="CompareVersion">
      <MemberSignature Language="C#" Value="public int CompareVersion (System.Fabric.ResolvedServicePartition other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int32 CompareVersion(class System.Fabric.ResolvedServicePartition other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ResolvedServicePartition.CompareVersion(System.Fabric.ResolvedServicePartition)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompareVersion (other As ResolvedServicePartition) As Integer" />
      <MemberSignature Language="F#" Value="member this.CompareVersion : System.Fabric.ResolvedServicePartition -&gt; int" Usage="resolvedServicePartition.CompareVersion other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.ResolvedServicePartition" />
      </Parameters>
      <Docs>
        <param name="other">
          <para>その他の解決済みのサービス パーティションを比較します。</para>
        </param>
        <summary>
          <para>解決済みのサービスの 2 つのパーティションを比較し、これは新しいを識別します。 </para>
        </summary>
        <returns>
          <para><see cref="T:System.Int32" /> を返します。</para>
        </returns>
        <remarks>
          <para><see cref="M:System.Fabric.ResolvedServicePartition.CompareVersion(System.Fabric.ResolvedServicePartition)" />メソッドはパラメーターを使用して、解決済みのサービス パーティション (RSP) の引数で使用<paramref name="other" />RSP はより最新の状態を識別するユーザーを有効にします。 返される値は 0 では、次の 2 つの RSPs 同じバージョンであることを示します。 1 は、その他の RSP が古いバージョンであることを示します。 -1 は、その他の RSP が新しいバージョンであることを示します。 </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>2 つ<see cref="T:System.Fabric.ResolvedServicePartition" />オブジェクト別のサービス パーティションからのものです。 これは、呼び出しを解決する 2 つのパーティション分割し、サービスが削除され、同じ名前で再作成される場合に発生することができます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;System.Fabric.ResolvedServiceEndpoint&gt; Endpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;class System.Fabric.ResolvedServiceEndpoint&gt; Endpoints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServicePartition.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoints As ICollection(Of ResolvedServiceEndpoint)" />
      <MemberSignature Language="F#" Value="member this.Endpoints : System.Collections.Generic.ICollection&lt;System.Fabric.ResolvedServiceEndpoint&gt;" Usage="System.Fabric.ResolvedServicePartition.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;System.Fabric.ResolvedServiceEndpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービス パーティションのエンドポイントを取得します。</para>
        </summary>
        <value>
          <para>コレクション<see cref="T:System.Fabric.ResolvedServiceEndpoint" />指定したサービス パーティション用です。</para>
        </value>
        <remarks>
          <para>解決済みのサービス エンドポイントには、ステートフル サービス レプリカまたはステートレス サービス インスタンスと、このレプリカがアクセスできるアドレス ロールが含まれています。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEndpoint">
      <MemberSignature Language="C#" Value="public System.Fabric.ResolvedServiceEndpoint GetEndpoint ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.ResolvedServiceEndpoint GetEndpoint() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ResolvedServicePartition.GetEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEndpoint () As ResolvedServiceEndpoint" />
      <MemberSignature Language="F#" Value="member this.GetEndpoint : unit -&gt; System.Fabric.ResolvedServiceEndpoint" Usage="resolvedServicePartition.GetEndpoint " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ResolvedServiceEndpoint</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>すべてのエンドポイントのコレクションではなく、単一のエンドポイントを返します。 </para>
        </summary>
        <returns>
          <para><see cref="T:System.Fabric.ResolvedServiceEndpoint" /> を返します。</para>
        </returns>
        <remarks>
          <para>多くの場合、だけのすべてのエンドポイントではなく単一のエンドポイントです。 サービスがステートレスの場合は、ランダムなエンドポイントを返します。 サービスがステートフルなサービスの場合よりも、サービス パーティションのプライマリ レプリカがリッスンするエンドポイントを返します。 現在プライマリ レプリカが存在しない場合にスローに注意してください<see cref="T:System.Fabric.FabricException" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Info">
      <MemberSignature Language="C#" Value="public System.Fabric.ServicePartitionInformation Info { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ServicePartitionInformation Info" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServicePartition.Info" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Info As ServicePartitionInformation" />
      <MemberSignature Language="F#" Value="member this.Info : System.Fabric.ServicePartitionInformation" Usage="System.Fabric.ResolvedServicePartition.Info" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServicePartitionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>解決されたサービスのパーティションに関する情報を取得します。</para>
        </summary>
        <value>解決されたか、サービスのパーティションに関する情報。</value>
        <remarks>
          <para>
            別のサービス パーティションを指定できます<see cref="T:System.Fabric.ServicePartitionKind" />です。
            サービス パーティションについては、パーティションに関する詳細な情報を取得する場合は、正しい派生型にキャストできます。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServicePartition.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.ResolvedServicePartition.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービス インスタンスの名前を取得します。</para>
        </summary>
        <value>
          <para>サービス インスタンスの名前です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>