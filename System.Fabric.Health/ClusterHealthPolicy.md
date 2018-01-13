<Type Name="ClusterHealthPolicy" FullName="System.Fabric.Health.ClusterHealthPolicy">
  <TypeSignature Language="C#" Value="public class ClusterHealthPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterHealthPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ClusterHealthPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterHealthPolicy" />
  <TypeSignature Language="F#" Value="type ClusterHealthPolicy = class" />
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
      <para>クラスターまたはクラスター ノードの正常性を評価する正常性ポリシーを定義します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterHealthPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealthPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>既定では、エラーまたは警告が許容されません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeHealthPolicyMap">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationTypeHealthPolicyMap ApplicationTypeHealthPolicyMap { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationTypeHealthPolicyMap ApplicationTypeHealthPolicyMap" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthPolicy.ApplicationTypeHealthPolicyMap" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeHealthPolicyMap As ApplicationTypeHealthPolicyMap" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeHealthPolicyMap : System.Fabric.Health.ApplicationTypeHealthPolicyMap" Usage="System.Fabric.Health.ClusterHealthPolicy.ApplicationTypeHealthPolicyMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationTypeHealthPolicyMap</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            アプリケーションの種類名ごとに MaxPercentUnhealthyApplications でマップを取得します。 
            </para>
        </summary>
        <value>
          <para>アプリケーション型正常性ポリシー マップ MaxPercentUnhealthyApplications とアプリケーションの種類名ごとです。</para>
        </value>
        <remarks>
          <para>アプリケーションの種類の正常性ポリシー マップは、特殊なアプリケーションの種類を記述するクラスターの正常性評価で使用できます。既定では、すべてのアプリケーションのプールに配置し、を使用して評価<see cref="P:System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />です。1 つまたは複数のアプリケーションの種類の特殊なし、する必要がありますを別の方法で扱われる、グローバル プールから取得およびできますマップで、アプリケーションの型名に関連付けられている割合に対して評価されます。たとえば、クラスターには、異なる種類の数千ものアプリケーションがあり、特別なアプリケーションの種類の制御アプリケーション インスタンスの数はわずかです。制御アプリケーションがエラー状態になることはありません。そのユーザーは、いくつかの障害を許容するように 20% が"ControlApplicationType"、MaxPercentUnhealthyApplications を 0 に設定するアプリケーションの種類に対してグローバル MaxPercentUnhealthyApplications を指定できます。このようにすると、多くのアプリケーションのうちのいくつかが異常でも、グローバルな異常のパーセンテージを下回っている場合、クラスターは警告と評価されます。警告の正常性状態はクラスターのアップグレードや、エラーの正常性状態によりトリガーされる他の監視には影響しません。エラーの 1 つでも管理アプリケーションはクラスターの正常性エラーがロールバックまたは、クラスターのアップグレードを妨げるです。</para>&gt;<para>マップで定義されているアプリケーションの種類、すべてのアプリケーション インスタンスが作成され、アプリケーションのグローバル プール外です。これらは、マップの特定の MaxPercentUnhealthyApplications を使用して、該当するアプリケーションの種類のアプリケーションの総数に基づいて評価されます。アプリケーションのすべての残りの部分は、グローバル プール内に残りますされ、MaxPercentUnhealthyApplications で評価されます。</para><para>クラスター マニフェストでは、特定のアプリケーションの種類のエントリを定義するに FabricSettings 内のエントリを追加のパラメーター プレフィックス「ApplicationTypeMaxPercentUnhealthyApplications-」続けてによって形成される名前を持つアプリケーションの種類の名前です。</para> <para>MaxPercentUnhealthyApplications 既定値を評価に使用するアプリケーションの種類のポリシーが指定されていない場合</para>。<para>EnableApplicationTypeHealthEvaluation で、クラスターが構成されている場合にのみ、アプリケーションの種類の正常性評価が行われます<languageKeyword>true</languageKeyword>です。既定では、設定を無効にします。</para></remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsiderWarningAsError">
      <MemberSignature Language="C#" Value="public bool ConsiderWarningAsError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ConsiderWarningAsError" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthPolicy.ConsiderWarningAsError" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsiderWarningAsError As Boolean" />
      <MemberSignature Language="F#" Value="member this.ConsiderWarningAsError : bool with get, set" Usage="System.Fabric.Health.ClusterHealthPolicy.ConsiderWarningAsError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定、<see cref="T:System.Boolean" />エラーとして重大度が同じで、警告状態を持つレポートを扱う必要があるかどうかを決定します。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>場合は警告状態を持つレポートをエラーとして扱う必要があります<languageKeyword>false</languageKeyword>場合は警告をエラーとして扱うことはできません。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyApplications">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyApplications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyApplications" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyApplications As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyApplications : byte with get, set" Usage="System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または異常なアプリケーションの許可される最大の割合を設定します。</para>
        </summary>
        <value>
          <para>許容される異常なアプリケーションの割合の最大値。 有効な値は、0 から 100 までの整数値です。</para>
        </value>
        <remarks>
          <para>
            パーセンテージは、異常な可能性のあるアプリケーションの最大許容パーセンテージを表します。この値を超えるとクラスターはエラーの状態と見なされます。 許容パーセンテージ内であっても、1 つ以上の異常なアプリケーションがある場合は、正常性は Warning として評価されます。
            これには、計算に含まれているアプリケーションの種類のすべてのアプリケーションの除外、クラスターに配置されたアプリケーションの総数に対して異常なアプリケーションの数で割ることによって、<see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" />です。
            切り上げ計算が実行され、少数のアプリケーションに対する 1 つのエラーは許容されます。 既定のパーセンテージは 0 です。
            </para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>指定した値は、0 から 100 までの整数値の範囲外でした。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyNodes : byte with get, set" Usage="System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または異常なノードの最大許容パーセンテージを設定します。</para>
        </summary>
        <value>
          <para>許容される異常なノードの割合の最大値。 有効な値は、0 から 100 までの整数値です。</para>
        </value>
        <remarks>
          <para>
            パーセンテージは、異常な可能性のあるノードの最大許容パーセンテージを表します。この値を超えるとクラスターはエラーの状態と見なされます。 許容パーセンテージ内であっても、1 つ以上の異常なノードがある場合は、正常性は Warning として評価されます。
            これは、クラスター内のノードの総数に対して異常なノードの数で割ることによって計算されます。
            切り上げ計算が実行され、少数のノードに対する 1 つのエラーは許容されます。 既定のパーセンテージは 0 です。
            </para>
          <para>大規模なクラスターでは、ダウンしているか修復を必要とするノードがいくつか必ず存在するため、それが許容されるようにこのパーセンテージを構成する必要があります。</para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>指定した値は、0 から 100 までの整数値の範囲外でした。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealthPolicy.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="clusterHealthPolicy.ToString " />
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
            クラスターの正常性ポリシーの文字列表現を取得します。
            </summary>
        <returns>クラスターの正常性ポリシーの文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>