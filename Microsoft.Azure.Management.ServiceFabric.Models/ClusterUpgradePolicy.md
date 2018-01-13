<Type Name="ClusterUpgradePolicy" FullName="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy">
  <TypeSignature Language="C#" Value="public class ClusterUpgradePolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterUpgradePolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterUpgradePolicy" />
  <TypeSignature Language="F#" Value="type ClusterUpgradePolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            クラスターのアップグレード ポリシー
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterUpgradePolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ClusterUpgradePolicy クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterUpgradePolicy (string upgradeReplicaSetCheckTimeout, string healthCheckWaitDuration, string healthCheckStableDuration, string healthCheckRetryTimeout, string upgradeTimeout, string upgradeDomainTimeout, Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy healthPolicy, Nullable&lt;bool&gt; overrideUserUpgradePolicy = null, Nullable&lt;bool&gt; forceRestart = null, Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy deltaHealthPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string upgradeReplicaSetCheckTimeout, string healthCheckWaitDuration, string healthCheckStableDuration, string healthCheckRetryTimeout, string upgradeTimeout, string upgradeDomainTimeout, class Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy healthPolicy, valuetype System.Nullable`1&lt;bool&gt; overrideUserUpgradePolicy, valuetype System.Nullable`1&lt;bool&gt; forceRestart, class Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy deltaHealthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy,System.Nullable{System.Boolean},System.Nullable{System.Boolean},Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (upgradeReplicaSetCheckTimeout As String, healthCheckWaitDuration As String, healthCheckStableDuration As String, healthCheckRetryTimeout As String, upgradeTimeout As String, upgradeDomainTimeout As String, healthPolicy As ClusterHealthPolicy, Optional overrideUserUpgradePolicy As Nullable(Of Boolean) = null, Optional forceRestart As Nullable(Of Boolean) = null, Optional deltaHealthPolicy As ClusterUpgradeDeltaHealthPolicy = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy : string * string * string * string * string * string * Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy -&gt; Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy (upgradeReplicaSetCheckTimeout, healthCheckWaitDuration, healthCheckStableDuration, healthCheckRetryTimeout, upgradeTimeout, upgradeDomainTimeout, healthPolicy, overrideUserUpgradePolicy, forceRestart, deltaHealthPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="upgradeReplicaSetCheckTimeout" Type="System.String" />
        <Parameter Name="healthCheckWaitDuration" Type="System.String" />
        <Parameter Name="healthCheckStableDuration" Type="System.String" />
        <Parameter Name="healthCheckRetryTimeout" Type="System.String" />
        <Parameter Name="upgradeTimeout" Type="System.String" />
        <Parameter Name="upgradeDomainTimeout" Type="System.String" />
        <Parameter Name="healthPolicy" Type="Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy" />
        <Parameter Name="overrideUserUpgradePolicy" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="forceRestart" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="deltaHealthPolicy" Type="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="upgradeReplicaSetCheckTimeout">.Net を表す、レプリカ セットのアップグレードが完了するタイムアウト、TimeSpan</param>
        <param name="healthCheckWaitDuration">.Net を表すことの正常性チェックを実行する前に、アップグレード ドメインの完了後に待機する時間の長さ、TimeSpan</param>
        <param name="healthCheckStableDuration">.Net を表す、正常性チェックの継続的に渡す必要がある時間の長さ、TimeSpan</param>
        <param name="healthCheckRetryTimeout">.Net を表す、正常性チェックの継続的に失敗する可能性がある時間の長さ、TimeSpan</param>
        <param name="upgradeTimeout">アップグレードのタイムアウトを表します .Net TimeSpan</param>
        <param name="upgradeDomainTimeout">.Net を表すことのすべてのアップグレード ドメイン タイムアウト、TimeSpan</param>
        <param name="healthPolicy">クラスターの正常性ポリシー</param>
        <param name="overrideUserUpgradePolicy">ユーザー定義のアップグレード ポリシーを使用するか</param>
        <param name="forceRestart">有無を再起動するノードを強制的に</param>
        <param name="deltaHealthPolicy">デルタの正常性ポリシー</param>
        <summary>
            ClusterUpgradePolicy クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeltaHealthPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy DeltaHealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy DeltaHealthPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.DeltaHealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property DeltaHealthPolicy As ClusterUpgradeDeltaHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.DeltaHealthPolicy : Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.DeltaHealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deltaHealthPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデルタの正常性ポリシーの設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceRestart">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ForceRestart { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ForceRestart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.ForceRestart" />
      <MemberSignature Language="VB.NET" Value="Public Property ForceRestart As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ForceRestart : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.ForceRestart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="forceRestart")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Force ノードか再起動を取得または設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckRetryTimeout">
      <MemberSignature Language="C#" Value="public string HealthCheckRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HealthCheckRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.HealthCheckRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckRetryTimeout As String" />
      <MemberSignature Language="F#" Value="member this.HealthCheckRetryTimeout : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.HealthCheckRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="healthCheckRetryTimeout")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            継続的に正常性チェックが失敗する、.Net を表すことは、時間の長さを設定を取得または TimeSpan
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckStableDuration">
      <MemberSignature Language="C#" Value="public string HealthCheckStableDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HealthCheckStableDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.HealthCheckStableDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckStableDuration As String" />
      <MemberSignature Language="F#" Value="member this.HealthCheckStableDuration : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.HealthCheckStableDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="healthCheckStableDuration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または時間の長さを設定する正常性チェックが継続的に渡す必要があります、.Net を表す TimeSpan
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckWaitDuration">
      <MemberSignature Language="C#" Value="public string HealthCheckWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HealthCheckWaitDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.HealthCheckWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckWaitDuration As String" />
      <MemberSignature Language="F#" Value="member this.HealthCheckWaitDuration : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.HealthCheckWaitDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="healthCheckWaitDuration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            正常性を実行する前に、アップグレード ドメインの完了後に待機する時間の長さが確認を取得または設定、.Net を表す TimeSpan
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ClusterHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.HealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="healthPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.ClusterHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクラスターの正常性ポリシーの設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OverrideUserUpgradePolicy">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; OverrideUserUpgradePolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; OverrideUserUpgradePolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.OverrideUserUpgradePolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property OverrideUserUpgradePolicy As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.OverrideUserUpgradePolicy : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.OverrideUserUpgradePolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="overrideUserUpgradePolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            かにユーザー定義のアップグレード ポリシーを使用して、取得または設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainTimeout">
      <MemberSignature Language="C#" Value="public string UpgradeDomainTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeDomainTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.UpgradeDomainTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeDomainTimeout As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainTimeout : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.UpgradeDomainTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="upgradeDomainTimeout")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タイムアウト設定を取得またはアップグレードの任意のドメインを表します .Net TimeSpan
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeReplicaSetCheckTimeout">
      <MemberSignature Language="C#" Value="public string UpgradeReplicaSetCheckTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeReplicaSetCheckTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.UpgradeReplicaSetCheckTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeReplicaSetCheckTimeout As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeReplicaSetCheckTimeout : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.UpgradeReplicaSetCheckTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="upgradeReplicaSetCheckTimeout")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タイムアウトの設定を取得または .Net を表す、レプリカ セットのアップグレードが完了する、TimeSpan
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeTimeout">
      <MemberSignature Language="C#" Value="public string UpgradeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.UpgradeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeTimeout As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeTimeout : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.UpgradeTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="upgradeTimeout")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アップグレードのタイムアウトを取得または設定が .Net を表す TimeSpan
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="clusterUpgradePolicy.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>