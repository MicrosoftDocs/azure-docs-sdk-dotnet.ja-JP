<Type Name="StatefulServiceContext" FullName="System.Fabric.StatefulServiceContext">
  <TypeSignature Language="C#" Value="public sealed class StatefulServiceContext : System.Fabric.ServiceContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatefulServiceContext extends System.Fabric.ServiceContext" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.StatefulServiceContext" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatefulServiceContext&#xA;Inherits ServiceContext" />
  <TypeSignature Language="F#" Value="type StatefulServiceContext = class&#xA;    inherit ServiceContext" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.ServiceContext</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            下にあるステートフルなサービスが動作しているサービス コンテキストを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatefulServiceContext (System.Fabric.NodeContext nodeContext, System.Fabric.ICodePackageActivationContext codePackageActivationContext, string serviceTypeName, Uri serviceName, byte[] initializationData, Guid partitionId, long replicaId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.NodeContext nodeContext, class System.Fabric.ICodePackageActivationContext codePackageActivationContext, string serviceTypeName, class System.Uri serviceName, unsigned int8[] initializationData, valuetype System.Guid partitionId, int64 replicaId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.StatefulServiceContext.#ctor(System.Fabric.NodeContext,System.Fabric.ICodePackageActivationContext,System.String,System.Uri,System.Byte[],System.Guid,System.Int64)" />
      <MemberSignature Language="F#" Value="new System.Fabric.StatefulServiceContext : System.Fabric.NodeContext * System.Fabric.ICodePackageActivationContext * string * Uri * byte[] * Guid * int64 -&gt; System.Fabric.StatefulServiceContext" Usage="new System.Fabric.StatefulServiceContext (nodeContext, codePackageActivationContext, serviceTypeName, serviceName, initializationData, partitionId, replicaId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeContext" Type="System.Fabric.NodeContext" />
        <Parameter Name="codePackageActivationContext" Type="System.Fabric.ICodePackageActivationContext" />
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="nodeContext">ステートレス サービス インスタンスが実行されているノードに関する情報を含むノードのコンテキスト。</param>
        <param name="codePackageActivationContext">コード パッケージのアクティベーション コンテキスト サービス マニフェストと現在アクティブ化されたコード パッケージからの情報を格納しているコンテキスト ID など、like の作業ディレクトリです。</param>
        <param name="serviceTypeName">サービス型の名前。</param>
        <param name="serviceName">サービスの名前。</param>
        <param name="initializationData">サービスの初期化データ、サービスの作成者によって提供されるカスタムの初期化データを表します。</param>
        <param name="partitionId">パーティションの id。</param>
        <param name="replicaId">レプリカ ID</param>
        <summary>
            <see cref="T:System.Fabric.StatefulServiceContext" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaId">
      <MemberSignature Language="C#" Value="public long ReplicaId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.StatefulServiceContext.ReplicaId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaId : int64" Usage="System.Fabric.StatefulServiceContext.ReplicaId" />
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
            ステートフル サービス レプリカ ID を取得します
            </summary>
        <value>ステートフル サービス レプリカ ID</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>