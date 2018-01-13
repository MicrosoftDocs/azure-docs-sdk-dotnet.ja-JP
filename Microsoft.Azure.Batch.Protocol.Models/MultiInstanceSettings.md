<Type Name="MultiInstanceSettings" FullName="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings">
  <TypeSignature Language="C#" Value="public class MultiInstanceSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MultiInstanceSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiInstanceSettings" />
  <TypeSignature Language="F#" Value="type MultiInstanceSettings = class" />
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
            マルチ インスタンスのタスクを実行する方法を指定する設定です。
            </summary>
    <remarks>
            マルチ インスタンスのタスクは通常、MPI タスクをサポートするために使用されます。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiInstanceSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.#ctor" />
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
            MultiInstanceSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiInstanceSettings (string coordinationCommandLine, Nullable&lt;int&gt; numberOfInstances = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; commonResourceFiles = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string coordinationCommandLine, valuetype System.Nullable`1&lt;int32&gt; numberOfInstances, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; commonResourceFiles) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.#ctor(System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResourceFile})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (coordinationCommandLine As String, Optional numberOfInstances As Nullable(Of Integer) = null, Optional commonResourceFiles As IList(Of ResourceFile) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings : string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings" Usage="new Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings (coordinationCommandLine, numberOfInstances, commonResourceFiles)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="coordinationCommandLine" Type="System.String" />
        <Parameter Name="numberOfInstances" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="commonResourceFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;" />
      </Parameters>
      <Docs>
        <param name="coordinationCommandLine">プライマリを調整するときに有効にするすべてのコンピューティング ノード上で実行するコマンド ラインでは、メイン タスクのコマンドを実行します。</param>
        <param name="numberOfInstances">タスクに必要なコンピューター ノードの数。</param>
        <param name="commonResourceFiles">Batch service は調整のコマンドラインを実行する前にダウンロードされるファイルの一覧。</param>
        <summary>
            MultiInstanceSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; CommonResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; CommonResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.CommonResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.CommonResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.CommonResourceFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commonResourceFiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または調整のコマンドラインを実行する前に、バッチ サービスをダウンロードするファイルの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            一般的なリソース ファイルとリソース ファイルのタスクの違いは、プライマリののみタスク リソース ファイルがダウンロードされ、プライマリを含むすべてのサブタスクの一般的なリソース ファイルにダウンロードされます。 なお、これらのリソース ファイルは、タスクの作業ディレクトリにダウンロードされませんが、代わりに、タスクのルート ディレクトリ (作業ディレクトリの上の 1 つのディレクトリ) にダウンロードされます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CoordinationCommandLine">
      <MemberSignature Language="C#" Value="public string CoordinationCommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CoordinationCommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.CoordinationCommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CoordinationCommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CoordinationCommandLine : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.CoordinationCommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="coordinationCommandLine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または有効にして、プライマリが主なタスクのコマンドを実行するときに調整するためのすべてのコンピューティング ノード上で実行するコマンドラインを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            一般的な調整のコマンドラインは、バック グラウンド サービスを起動し、サービスがノード間のメッセージを処理する準備ができていることを確認します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfInstances">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfInstances { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfInstances" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.NumberOfInstances" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberOfInstances As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfInstances : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.NumberOfInstances" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numberOfInstances")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクに必要なコンピューティング ノードの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            省略した場合、既定値は 1 です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="multiInstanceSettings.Validate " />
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
  </Members>
</Type>