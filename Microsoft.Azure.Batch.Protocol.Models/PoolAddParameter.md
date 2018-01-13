<Type Name="PoolAddParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter">
  <TypeSignature Language="C#" Value="public class PoolAddParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolAddParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolAddParameter" />
  <TypeSignature Language="F#" Value="type PoolAddParameter = class" />
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
            Azure Batch サービスを追加するにプールします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolAddParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.#ctor" />
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
            PoolAddParameter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolAddParameter (string id, string vmSize, string displayName = null, Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration cloudServiceConfiguration = null, Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration virtualMachineConfiguration = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;int&gt; targetDedicatedNodes = null, Nullable&lt;int&gt; targetLowPriorityNodes = null, Nullable&lt;bool&gt; enableAutoScale = null, string autoScaleFormula = null, Nullable&lt;TimeSpan&gt; autoScaleEvaluationInterval = null, Nullable&lt;bool&gt; enableInterNodeCommunication = null, Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration networkConfiguration = null, Microsoft.Azure.Batch.Protocol.Models.StartTask startTask = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences = null, System.Collections.Generic.IList&lt;string&gt; applicationLicenses = null, Nullable&lt;int&gt; maxTasksPerNode = null, Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy taskSchedulingPolicy = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; userAccounts = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string vmSize, string displayName, class Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration cloudServiceConfiguration, class Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration virtualMachineConfiguration, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityNodes, valuetype System.Nullable`1&lt;bool&gt; enableAutoScale, string autoScaleFormula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoScaleEvaluationInterval, valuetype System.Nullable`1&lt;bool&gt; enableInterNodeCommunication, class Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration networkConfiguration, class Microsoft.Azure.Batch.Protocol.Models.StartTask startTask, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences, class System.Collections.Generic.IList`1&lt;string&gt; applicationLicenses, valuetype System.Nullable`1&lt;int32&gt; maxTasksPerNode, class Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy taskSchedulingPolicy, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; userAccounts, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.#ctor(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration,Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration,System.Nullable{System.TimeSpan},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.String,System.Nullable{System.TimeSpan},System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration,Microsoft.Azure.Batch.Protocol.Models.StartTask,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.CertificateReference},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference},System.Collections.Generic.IList{System.String},System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.UserAccount},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter : string * string * string * Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration * Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * string * Nullable&lt;TimeSpan&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration * Microsoft.Azure.Batch.Protocol.Models.StartTask * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter (id, vmSize, displayName, cloudServiceConfiguration, virtualMachineConfiguration, resizeTimeout, targetDedicatedNodes, targetLowPriorityNodes, enableAutoScale, autoScaleFormula, autoScaleEvaluationInterval, enableInterNodeCommunication, networkConfiguration, startTask, certificateReferences, applicationPackageReferences, applicationLicenses, maxTasksPerNode, taskSchedulingPolicy, userAccounts, metadata)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="cloudServiceConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration" />
        <Parameter Name="virtualMachineConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="targetDedicatedNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="enableAutoScale" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="autoScaleFormula" Type="System.String" />
        <Parameter Name="autoScaleEvaluationInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="enableInterNodeCommunication" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="networkConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration" />
        <Parameter Name="startTask" Type="Microsoft.Azure.Batch.Protocol.Models.StartTask" />
        <Parameter Name="certificateReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt;" />
        <Parameter Name="applicationPackageReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;" />
        <Parameter Name="applicationLicenses" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="maxTasksPerNode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="taskSchedulingPolicy" Type="Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy" />
        <Parameter Name="userAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt;" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
      </Parameters>
      <Docs>
        <param name="id">アカウント内のプールを一意に識別する文字列。</param>
        <param name="vmSize">プール内の仮想マシンのサイズ。 プール内の仮想マシンのサイズはすべて同じです。</param>
        <param name="displayName">プールの表示名。</param>
        <param name="cloudServiceConfiguration">プールのクラウドサービス構成。</param>
        <param name="virtualMachineConfiguration">プールの仮想マシン構成。</param>
        <param name="resizeTimeout">プールにコンピューティング ノードの割り当てのタイムアウト。</param>
        <param name="targetDedicatedNodes">専用の目的の数は、プール内のノードを計算します。</param>
        <param name="targetLowPriorityNodes">目的の優先度の低い数は、プール内のノードを計算します。</param>
        <param name="enableAutoScale">かどうか、プールのサイズは、時間の経過と共に自動的に調整する必要があります。</param>
        <param name="autoScaleFormula">プール内の計算ノードの必要な数の式。</param>
        <param name="autoScaleEvaluationInterval">自動スケールの数式に従ってプールのサイズを自動的に調整する時間間隔。</param>
        <param name="enableInterNodeCommunication">かどうか、プールは、ノード間の直接通信を許可します。</param>
        <param name="networkConfiguration">プールのネットワーク構成。</param>
        <param name="startTask">各コンピューティング ノードで、プールに参加を実行する指定されたタスク。</param>
        <param name="certificateReferences">プール内の各コンピューティング ノードにインストールされている証明書の一覧です。</param>
        <param name="applicationPackageReferences">プール内の各コンピューティング ノードにインストールされているアプリケーション パッケージの一覧。</param>
        <param name="applicationLicenses">アプリケーションの一覧のライセンスは、バッチ サービスは、プール内の各コンピューティング ノードで使用できるようにします。</param>
        <param name="maxTasksPerNode">プール内の単一コンピューティング ノードで同時に実行できるタスクの最大数。</param>
        <param name="taskSchedulingPolicy">どのタスクはプール内のコンピューティング ノード間で分散されます。</param>
        <param name="userAccounts">プール内の各ノード上に作成されるユーザー アカウントの一覧です。</param>
        <param name="metadata">メタデータとしてプールに関連付けられている名前と値のペアの一覧。</param>
        <summary>
            PoolAddParameter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLicenses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ApplicationLicenses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ApplicationLicenses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.ApplicationLicenses" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationLicenses As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ApplicationLicenses : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.ApplicationLicenses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationLicenses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリケーションのライセンスの一覧をバッチ サービスは、プール内の各コンピューティング ノードで使用できるように設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            アプリケーションのライセンスの一覧は、使用できる Batch サービス アプリケーションのライセンスのサブセットである必要があります。 これはサポートされていない要求されるライセンスと、プールの作成は失敗します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.ApplicationPackageReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationPackageReferences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の各コンピューティング ノードにインストールされているアプリケーション パッケージの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleEvaluationInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; AutoScaleEvaluationInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; AutoScaleEvaluationInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.AutoScaleEvaluationInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleEvaluationInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.AutoScaleEvaluationInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.AutoScaleEvaluationInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoScaleEvaluationInterval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または自動スケールの数式に従ってプールのサイズを自動的に調整するための時間間隔を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は、15 分です。 最小値と最大値は、それぞれ 5 分と 168 時間です。 小さい値 5 分 168 時間より大きいかを指定すると、バッチ サービスは; エラーを返しますREST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleFormula">
      <MemberSignature Language="C#" Value="public string AutoScaleFormula { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoScaleFormula" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.AutoScaleFormula" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleFormula As String" />
      <MemberSignature Language="F#" Value="member this.AutoScaleFormula : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.AutoScaleFormula" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoScaleFormula")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の式の目的のコンピューティング ノードの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティがありますいない enableAutoScale が false に設定されているかどうかを指定します。 EnableAutoScale が設定されている場合は、必須を true にします。 数式は、プールが作成される前に、有効性に対してチェックされます。 数式が有効でない場合、Batch service は詳細なエラー情報が要求を拒否します。 この式の指定に関する詳細については、'自動的に Azure Batch プール内のノードをコンピューティング スケール' を参照してください (https://azure.microsoft.com/documentation/articles/batch-automatic-scaling/)。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.CertificateReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateReferences As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.CertificateReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.CertificateReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateReferences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の各コンピューティング ノードにインストールされている証明書の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            Windows では、ノードを計算するため、バッチ サービスは、場所と指定された証明書ストアに証明書をインストールします。 Linux 計算ノードでは、証明書は、タスクの作業ディレクトリと変数 AZ_BATCH_CERTIFICATES_DIR がこの場所にクエリするタスクに指定された環境の内部ディレクトリに保存されます。 'RemoteUser' の可視性を持つ証明書は、'certs' ディレクトリは、ユーザーのホーム ディレクトリに作成 (など/home/{ユーザー名}/certs) および証明書はそのディレクトリに配置します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudServiceConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration CloudServiceConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration CloudServiceConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.CloudServiceConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudServiceConfiguration As CloudServiceConfiguration" />
      <MemberSignature Language="F#" Value="member this.CloudServiceConfiguration : Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.CloudServiceConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cloudServiceConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールをクラウド サービスの構成を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティと virtualMachineConfiguration は相互に排他的とプロパティのいずれかを指定する必要があります。 このプロパティは、Batch アカウントが、poolAllocationMode プロパティ 'UserSubscription' に設定して作成されたかどうかを指定します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールの表示名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            表示名は一意でない必要があり、最大で 1,024 の最大長の Unicode 文字を含めることができます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScale">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableAutoScale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableAutoScale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.EnableAutoScale" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableAutoScale As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableAutoScale : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.EnableAutoScale" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enableAutoScale")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または時間の経過と共に、プールのサイズを自動的に調整するかどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            False の場合、targetDedicateNodes と targetLowPriorityNodes の少なくとも 1 つ指定する必要があります。 True の場合は、autoScaleFormula プロパティは必須と数式に従ってプールが自動的にサイズ変更します。 既定値は false です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableInterNodeCommunication">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableInterNodeCommunication { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableInterNodeCommunication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.EnableInterNodeCommunication" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableInterNodeCommunication As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableInterNodeCommunication : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.EnableInterNodeCommunication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enableInterNodeCommunication")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールがノード間で直接通信を許可するかどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            ノード間通信を有効にすると、プールのノードの展開の制限により、プールの最大サイズが制限されます。 これにより、プールが必要なサイズに到達しない可能性があります。 既定値は false です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアカウント内のプールを一意に識別する文字列を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            ID は、ハイフン、アンダー スコアを含む、英数字の任意の組み合わせを含めることができ、64 を超える文字を含めることはできません。 ID は大文字と小文字を区別 (つまり、大文字小文字によってのみが異なる 2 つのプール Id アカウント内ではありません必要があります)。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTasksPerNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTasksPerNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTasksPerNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.MaxTasksPerNode" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTasksPerNode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTasksPerNode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.MaxTasksPerNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxTasksPerNode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の 1 つのコンピューティング ノードで同時に実行できるタスクの最大数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は 1 です。 この設定の最大値は、(vmSize 設定)、プール内の計算ノードのサイズによって異なります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはメタデータとしてプールに関連付けられている名前と値のペアの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            バッチ サービスがメタデータに意味を割り当てませんこれは、ユーザー コードを使用するためだけです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration NetworkConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration NetworkConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.NetworkConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkConfiguration As NetworkConfiguration" />
      <MemberSignature Language="F#" Value="member this.NetworkConfiguration : Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.NetworkConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.ResizeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ResizeTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ResizeTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.ResizeTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resizeTimeout")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールに割り当てるコンピューティング ノードの場合のタイムアウトを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このタイムアウトは手動スケール; にのみ適用されます。影響を与えません enableAutoScale が設定されている場合に true に設定します。 既定値は、15 分です。
            最小値は、5 分です。 5 分より小さい値を指定する場合、Batch service が; エラーを返しますREST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Batch.Protocol.Models.StartTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.StartTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.StartTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または各コンピューティング ノードで、プールに参加を実行する指定されたタスクを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            タスクは、プールに、または、ノードが再起動されたときに、ノードが追加されたときに実行されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDedicatedNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetDedicatedNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetDedicatedNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.TargetDedicatedNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDedicatedNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetDedicatedNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.TargetDedicatedNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetDedicatedNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールの目的専用のコンピューティング ノードの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティがありますいない enableAutoScale が設定されているかどうかは指定されたを true にします。 EnableAutoScale が false に設定されている場合は、targetDedicatedNodes、targetLowPriorityNodes、またはその両方を設定する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLowPriorityNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetLowPriorityNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetLowPriorityNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.TargetLowPriorityNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetLowPriorityNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetLowPriorityNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.TargetLowPriorityNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetLowPriorityNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールに目的の優先度の低いコンピューティング ノードの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティがありますいない enableAutoScale が設定されているかどうかは指定されたを true にします。 EnableAutoScale が false に設定されている場合は、targetDedicatedNodes、targetLowPriorityNodes、またはその両方を設定する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskSchedulingPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy TaskSchedulingPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy TaskSchedulingPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.TaskSchedulingPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskSchedulingPolicy As TaskSchedulingPolicy" />
      <MemberSignature Language="F#" Value="member this.TaskSchedulingPolicy : Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.TaskSchedulingPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="taskSchedulingPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクのプール内のコンピューティング ノード間で配分する方法を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; UserAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; UserAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.UserAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAccounts As IList(Of UserAccount)" />
      <MemberSignature Language="F#" Value="member this.UserAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.UserAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userAccounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の各ノード上に作成されるユーザー アカウントの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="poolAddParameter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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
    <Member MemberName="VirtualMachineConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration VirtualMachineConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration VirtualMachineConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.VirtualMachineConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineConfiguration As VirtualMachineConfiguration" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineConfiguration : Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.VirtualMachineConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualMachineConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールの仮想マシンの構成を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティと cloudServiceConfiguration は相互に排他的とプロパティのいずれかを指定する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の仮想マシンのサイズを設定します。 プール内の仮想マシンのサイズはすべて同じです。
            </summary>
        <value>To be added.</value>
        <remarks>
            クラウド サービス プール (プール cloudServiceConfiguration で作成された) の仮想マシンの利用可能なサイズについては、クラウド サービス (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/) のサイズを参照してください。
            バッチには、ExtraSmall、A1V2 A2V2 を除くすべてのクラウド サービス VM サイズがサポートしています。 (プール virtualMachineConfiguration で作成した) 仮想マシンのマーケットプ レースからイメージを使用するプールの利用可能な VM サイズについては (Linux) (https://azure.microsoft.com/documentation/articles/ の仮想マシンのサイズを参照してください。仮想マシンの linux-サイズ/) または仮想マシン (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/) のサイズ。
            バッチには、STANDARD_A0 と premium storage (STANDARD_GS、STANDARD_DS、および STANDARD_DSV2 シリーズ) でそれらを除くすべての Azure VM サイズがサポートしています。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>