<Type Name="ResourceFile" FullName="Microsoft.Azure.Batch.Protocol.Models.ResourceFile">
  <TypeSignature Language="C#" Value="public class ResourceFile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceFile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ResourceFile" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceFile" />
  <TypeSignature Language="F#" Value="type ResourceFile = class" />
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
            コンピューティング ノードを Azure blob ストレージからダウンロードされるファイルです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceFile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ResourceFile.#ctor" />
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
            ・ リソースファイル クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceFile (string blobSource, string filePath, string fileMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string blobSource, string filePath, string fileMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ResourceFile.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobSource As String, filePath As String, Optional fileMode As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ResourceFile : string * string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.ResourceFile" Usage="new Microsoft.Azure.Batch.Protocol.Models.ResourceFile (blobSource, filePath, fileMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobSource" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileMode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blobSource">Azure Blob ストレージ内でのファイルの URL です。</param>
        <param name="filePath">タスクの作業ディレクトリに対して相対的、ファイルをダウンロードするコンピューティング ノード上の場所。</param>
        <param name="fileMode">8 進数形式でファイルのアクセス許可モード属性です。</param>
        <summary>
            ・ リソースファイル クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobSource">
      <MemberSignature Language="C#" Value="public string BlobSource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceFile.BlobSource" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobSource As String" />
      <MemberSignature Language="F#" Value="member this.BlobSource : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceFile.BlobSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blobSource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Blob ストレージ内でのファイルの URL を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            この URL は、匿名アクセスを使用して読み取り可能である必要があります。つまり、blob をダウンロードするときに、バッチ サービスは、資格情報を表示しません。 Azure ストレージ内の blob をこのような URL を取得する 2 つの方法があります。 Shared Access Signature (SAS)、blob に対する読み取り権限の許可を含めたり、パブリック アクセスを許可するには、blob またはコンテナーの ACL を設定します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FileMode">
      <MemberSignature Language="C#" Value="public string FileMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceFile.FileMode" />
      <MemberSignature Language="VB.NET" Value="Public Property FileMode As String" />
      <MemberSignature Language="F#" Value="member this.FileMode : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceFile.FileMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fileMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または 8 進数形式でファイルのアクセス許可モード属性を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティは、Linux 計算ノードにダウンロードされているファイルにのみ適用されます。 Windows のノードにダウンロードされます・ リソースファイルに対して指定されている場合、無視されます。 このプロパティは指定しない場合、Linux ノードの 0770 の既定値がファイルに適用されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePath">
      <MemberSignature Language="C#" Value="public string FilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceFile.FilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property FilePath As String" />
      <MemberSignature Language="F#" Value="member this.FilePath : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceFile.FilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードをタスクの作業ディレクトリに対して相対的、ファイルをダウンロードする場所を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ResourceFile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceFile.Validate " />
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