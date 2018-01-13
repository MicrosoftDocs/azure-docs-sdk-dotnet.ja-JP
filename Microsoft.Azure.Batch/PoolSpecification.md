<Type Name="PoolSpecification" FullName="Microsoft.Azure.Batch.PoolSpecification">
  <TypeSignature Language="C#" Value="public class PoolSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.PoolSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolSpecification" />
  <TypeSignature Language="F#" Value="type PoolSpecification = class&#xA;    interface ITransportObjectProvider&lt;PoolSpecification&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            プールを指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolSpecification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.PoolSpecification" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLicenses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ApplicationLicenses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ApplicationLicenses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.ApplicationLicenses" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationLicenses As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ApplicationLicenses : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.ApplicationLicenses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリケーションのライセンスの一覧をバッチ サービスは、プール内の各コンピューティング ノードで使用できるように設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            アプリケーションのライセンスの一覧は、使用できる Batch サービス アプリケーションのライセンスのサブセットである必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.ApplicationPackageReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ApplicationPackageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の各コンピューティング ノードにインストールされているアプリケーション パッケージの参照の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AutoScaleEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AutoScaleEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AutoScaleEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または時間の経過と共に、プールのサイズを自動的に調整するかどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>False の場合のいずれか、<see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetDedicatedComputeNodes" />または<see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetLowPriorityComputeNodes" />プロパティは必須です。</para>
          <para>True の場合、<see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleFormula" />プロパティは必須です。 プールは、数式に従って自動的にサイズ変更します。</para>
          <para>既定値は false です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleEvaluationInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; AutoScaleEvaluationInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; AutoScaleEvaluationInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEvaluationInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleEvaluationInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.AutoScaleEvaluationInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.AutoScaleEvaluationInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定によると、プール サイズを自動的に調整する時間間隔、<see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleFormula" />です。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は、15 分です。 最小値は、5 分です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleFormula">
      <MemberSignature Language="C#" Value="public string AutoScaleFormula { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoScaleFormula" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleFormula" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleFormula As String" />
      <MemberSignature Language="F#" Value="member this.AutoScaleFormula : string with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.AutoScaleFormula" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の式の目的のコンピューティング ノードの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>方法については自動スケールの数式を記述、https://azure.microsoft.com/documentation/articles/batch-automatic-scaling/ を参照してください。 場合、このプロパティは必須<see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" />設定が true にします。 AutoScaleEnabled が false の場合、null にする必要があります。</para>
          <para>数式は、プールが作成される前に、有効性に対してチェックされます。 コミットしようとすると、例外がスローされます、数式が有効でない場合、<see cref="T:Microsoft.Azure.Batch.PoolSpecification" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.CertificateReference&gt; CertificateReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.CertificateReference&gt; CertificateReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.CertificateReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateReferences As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.CertificateReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.CertificateReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.CertificateReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の各コンピューティング ノードにインストールされている証明書の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudServiceConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudServiceConfiguration CloudServiceConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.CloudServiceConfiguration CloudServiceConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.CloudServiceConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudServiceConfiguration As CloudServiceConfiguration" />
      <MemberSignature Language="F#" Value="member this.CloudServiceConfiguration : Microsoft.Azure.Batch.CloudServiceConfiguration with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.CloudServiceConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudServiceConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、<see cref="P:Microsoft.Azure.Batch.PoolSpecification.CloudServiceConfiguration" />プールします。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティで相互に排他的<see cref="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineConfiguration" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールの表示名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InterComputeNodeCommunicationEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; InterComputeNodeCommunicationEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; InterComputeNodeCommunicationEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.InterComputeNodeCommunicationEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property InterComputeNodeCommunicationEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.InterComputeNodeCommunicationEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.InterComputeNodeCommunicationEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールが、コンピューティング ノード間で直接通信を許可するかどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            ノード間通信を有効にすると、プールのノードの展開の制限により、プールの最大サイズが制限されます。 これにより、プールが必要なサイズに到達しない可能性があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTasksPerComputeNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTasksPerComputeNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTasksPerComputeNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.MaxTasksPerComputeNode" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTasksPerComputeNode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTasksPerComputeNode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.MaxTasksPerComputeNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の 1 つのコンピューティング ノードで同時に実行できるタスクの最大数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は 1 です。 この設定の最大値は、プール内の計算ノードのサイズによって異なります (、<see cref="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineSize" />プロパティ)。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはメタデータとしてプールに関連付けられている名前と値のペアの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.NetworkConfiguration NetworkConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.NetworkConfiguration NetworkConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.NetworkConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkConfiguration As NetworkConfiguration" />
      <MemberSignature Language="F#" Value="member this.NetworkConfiguration : Microsoft.Azure.Batch.NetworkConfiguration with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.NetworkConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.NetworkConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールのネットワーク構成を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ResizeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ResizeTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.ResizeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ResizeTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ResizeTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.ResizeTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールに割り当てるコンピューティング ノードの場合のタイムアウトを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>このタイムアウトは手動スケール; にのみ適用されます。あるされるときに有効<see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" />設定を true にします。</para>
          <para>既定値は、15 分です。 最小値は、5 分です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Batch.StartTask with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.StartTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.StartTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールを結合として各コンピューティング ノード上で実行するタスクを設定します。 タスクは、プールに、または、ノードが再起動されたときに、ノードが追加されたときに実行されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDedicated">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetDedicated { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetDedicated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.TargetDedicated" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDedicated As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetDedicated : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.TargetDedicated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Obsolete after 05/2017, use TargetDedicatedComputeNodes instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このプロパティは、別名を<see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetDedicatedComputeNodes" />は旧バージョンと互換性のためだけにサポートされています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDedicatedComputeNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetDedicatedComputeNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetDedicatedComputeNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.TargetDedicatedComputeNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDedicatedComputeNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetDedicatedComputeNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.TargetDedicatedComputeNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールの目的専用のコンピューティング ノードの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            場合、この設定を指定することはできません<see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" />設定が true に設定します。 このプロパティの少なくとも 1 つと<see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetLowPriorityComputeNodes" />場合に指定する必要があります<see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" />は false。 指定しない場合、既定値は 0 です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLowPriorityComputeNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetLowPriorityComputeNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetLowPriorityComputeNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.TargetLowPriorityComputeNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetLowPriorityComputeNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetLowPriorityComputeNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.TargetLowPriorityComputeNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールに目的の優先度の低いコンピューティング ノードの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            場合、この設定を指定することはできません<see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" />設定が true に設定します。 少なくとも 1 つの<see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetDedicatedComputeNodes" />場合、このプロパティを指定する必要がありますと<see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" />は false。 指定しない場合、既定値は 0 です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskSchedulingPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskSchedulingPolicy TaskSchedulingPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskSchedulingPolicy TaskSchedulingPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.TaskSchedulingPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskSchedulingPolicy As TaskSchedulingPolicy" />
      <MemberSignature Language="F#" Value="member this.TaskSchedulingPolicy : Microsoft.Azure.Batch.TaskSchedulingPolicy with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.TaskSchedulingPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskSchedulingPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクのプール内の計算ノード間で配分する方法を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.UserAccount&gt; UserAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.UserAccount&gt; UserAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.UserAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAccounts As IList(Of UserAccount)" />
      <MemberSignature Language="F#" Value="member this.UserAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.UserAccount&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.UserAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.UserAccount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の各ノード上に作成されるユーザー アカウントの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.VirtualMachineConfiguration VirtualMachineConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.VirtualMachineConfiguration VirtualMachineConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineConfiguration As VirtualMachineConfiguration" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineConfiguration : Microsoft.Azure.Batch.VirtualMachineConfiguration with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.VirtualMachineConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.VirtualMachineConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、<see cref="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineConfiguration" />プールのです。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティで相互に排他的<see cref="P:Microsoft.Azure.Batch.PoolSpecification.CloudServiceConfiguration" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineSize">
      <MemberSignature Language="C#" Value="public string VirtualMachineSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineSize As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineSize : string with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.VirtualMachineSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の仮想マシンのサイズを設定します。  プール内の仮想マシンのサイズはすべて同じです。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>クラウド サービス プールの仮想マシンの利用可能なサイズについて (で作成されたプール、 <see cref="P:Microsoft.Azure.Batch.PoolSpecification.CloudServiceConfiguration" />)、https://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/ を参照してください。 バッチには、ExtraSmall を除くすべてのクラウド サービス VM サイズがサポートしています。</para>
          <para>仮想マシンのマーケットプ レースからイメージを使用するプールの利用可能な VM サイズについては (で作成されたプール、 <see cref="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineConfiguration" />) https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/ または https:// を参照してくださいazure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/ です。 バッチには、STANDARD_A0 と premium storage (たとえば STANDARD_GS、STANDARD_DS、および STANDARD_DSV2 シリーズ) でそれらを除くすべての Azure VM サイズがサポートしています。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>