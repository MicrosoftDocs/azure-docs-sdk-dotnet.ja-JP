<Type Name="DeployedApplicationHealthStateChunk" FullName="System.Fabric.Health.DeployedApplicationHealthStateChunk">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationHealthStateChunk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationHealthStateChunk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedApplicationHealthStateChunk" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationHealthStateChunk" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealthStateChunk = class" />
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
            展開済みアプリケーションに関する基本的な正常性の情報を含む、展開済みアプリケーションの正常性の状態チャンクを表します。
            アプリケーションの子として含まれます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeployedServicePackageHealthStateChunks">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.DeployedServicePackageHealthStateChunkList DeployedServicePackageHealthStateChunks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.DeployedServicePackageHealthStateChunkList DeployedServicePackageHealthStateChunks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStateChunk.DeployedServicePackageHealthStateChunks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedServicePackageHealthStateChunks As DeployedServicePackageHealthStateChunkList" />
      <MemberSignature Language="F#" Value="member this.DeployedServicePackageHealthStateChunks : System.Fabric.Health.DeployedServicePackageHealthStateChunkList" Usage="System.Fabric.Health.DeployedApplicationHealthStateChunk.DeployedServicePackageHealthStateChunks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.DeployedServicePackageHealthStateChunkList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            展開済みサービス パッケージのヘルス状態チャンク子入力フィルターを適用するの一覧を取得します。
            </summary>
        <value>展開済みサービス パッケージのレプリカのヘルス状態の一覧は、入力のフィルターを適用する子を分割します。</value>
        <remarks>
          <para>既定では、子ない結果に含められます。 ユーザーは、必要な正常性アドインまたはその他の情報に基づく子の一部を含めるように要求できます。 たとえば、ユーザーは、ヘルス状態のエラーのあるすべての展開済みサービス パッケージを含める要求できます。
            フィルター値に関係なく、すべての子は、エンティティで集計された正常性が計算に使用されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStateChunk.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.DeployedApplicationHealthStateChunk.HealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            報告された状態のすべてのイベント、子、およびアプリケーションの正常性ポリシーに基づく計算された、展開されたアプリケーションの集計されたヘルス状態を取得します。
            </summary>
        <value>展開済みアプリケーションの集計された正常性状態</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStateChunk.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.DeployedApplicationHealthStateChunk.NodeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ノード名を取得します。
            </summary>
        <value>ノード名。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealthStateChunk.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedApplicationHealthStateChunk.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ヘルス状態のチャンクについて説明する文字列を作成します。
            </summary>
        <returns>ヘルス状態のチャンクの説明の文字列を指定します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>