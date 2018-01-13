<Type Name="OutputFile" FullName="Microsoft.Azure.Batch.Protocol.Models.OutputFile">
  <TypeSignature Language="C#" Value="public class OutputFile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OutputFile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.OutputFile" />
  <TypeSignature Language="VB.NET" Value="Public Class OutputFile" />
  <TypeSignature Language="F#" Value="type OutputFile = class" />
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
            バッチ サービスのタスク プロセスの実行が完了した後に Azure Batch ノードから別の場所にファイルをアップロードするための仕様。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputFile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OutputFile.#ctor" />
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
            OutputFile クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputFile (string filePattern, Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination destination, Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions uploadOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string filePattern, class Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination destination, class Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions uploadOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OutputFile.#ctor(System.String,Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination,Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (filePattern As String, destination As OutputFileDestination, uploadOptions As OutputFileUploadOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.OutputFile : string * Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination * Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.OutputFile" Usage="new Microsoft.Azure.Batch.Protocol.Models.OutputFile (filePattern, destination, uploadOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="filePattern" Type="System.String" />
        <Parameter Name="destination" Type="Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination" />
        <Parameter Name="uploadOptions" Type="Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions" />
      </Parameters>
      <Docs>
        <param name="filePattern">アップロードするファイルを示すパターン。</param>
        <param name="destination">出力ファイルのコピー先です。</param>
        <param name="uploadOptions">アップロード操作は、アップロードを実行する条件を含む追加のオプション。</param>
        <summary>
            OutputFile クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Destination">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination Destination { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination Destination" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.OutputFile.Destination" />
      <MemberSignature Language="VB.NET" Value="Public Property Destination As OutputFileDestination" />
      <MemberSignature Language="F#" Value="member this.Destination : Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.OutputFile.Destination" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destination")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または出力ファイルの保存先を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePattern">
      <MemberSignature Language="C#" Value="public string FilePattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.OutputFile.FilePattern" />
      <MemberSignature Language="VB.NET" Value="Public Property FilePattern As String" />
      <MemberSignature Language="F#" Value="member this.FilePattern : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.OutputFile.FilePattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filePattern")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアップロードするファイルを示すパターンを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            絶対パスはサポートされています。 相対パスでは、タスクの作業ディレクトリに対して相対的です。 次のワイルドカードはサポートされて: * 0 または以上の文字と一致する (パターン例の abc *、一致 abc または abcdef)、* * 任意のディレクトリと一致するか。 任意の 1 文字、角かっこ、[abc] と一致する 1 文字の範囲内の [a から c] と一致する 1 つの文字に一致します。 角かっこが指定されていない任意の文字を一致するように否定を含めることができます (たとえば [! abc] と一致する任意の文字が a、b、または c)。 ファイル名で始まる場合"です。"は既定では無視されますが、、、明示的に指定することによって照合される可能性があります (たとえば*.gif は一致しません。 a.gif、が。*です。gif されます)。 単純な例: * * \*.txt で始まっていない任意のファイルを一致する '.'.txt タスクの作業ディレクトリまたは任意のサブディレクトリで終了します。ファイル名にワイルドカード文字が含まれている場合をエスケープする必要が角かっこを使用して (たとえば abc [*] abc という名前のファイルが一致する*)。 注意してください両方 \、/のみ、Windows では、ディレクトリの区切り記号として扱われます/on Linux はします。 環境変数 (var % on Windows) または $var on Linux は、適用されているパターンの前に展開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions UploadOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions UploadOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.OutputFile.UploadOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property UploadOptions As OutputFileUploadOptions" />
      <MemberSignature Language="F#" Value="member this.UploadOptions : Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.OutputFile.UploadOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="uploadOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアップロード操作は、アップロードを実行する条件を含む追加のオプションを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OutputFile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="outputFile.Validate " />
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