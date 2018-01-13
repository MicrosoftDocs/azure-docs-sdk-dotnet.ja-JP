<Type Name="IndexingResult" FullName="Microsoft.Azure.Search.Models.IndexingResult">
  <TypeSignature Language="C#" Value="public class IndexingResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IndexingResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexingResult" />
  <TypeSignature Language="VB.NET" Value="Public Class IndexingResult" />
  <TypeSignature Language="F#" Value="type IndexingResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            1 つのドキュメントのインデックス作成操作の状態です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexingResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            IndexingResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexingResult (string key = null, string errorMessage = null, bool succeeded = false, int statusCode = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string key, string errorMessage, bool succeeded, int32 statusCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingResult.#ctor(System.String,System.String,System.Boolean,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional key As String = null, Optional errorMessage As String = null, Optional succeeded As Boolean = false, Optional statusCode As Integer = 0)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.IndexingResult : string * string * bool * int -&gt; Microsoft.Azure.Search.Models.IndexingResult" Usage="new Microsoft.Azure.Search.Models.IndexingResult (key, errorMessage, succeeded, statusCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="errorMessage" Type="System.String" />
        <Parameter Name="succeeded" Type="System.Boolean" />
        <Parameter Name="statusCode" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="key">インデックス作成の要求では、ドキュメントのキー。</param>
        <param name="errorMessage">キーによって識別されたドキュメントのインデックス作成操作が失敗した理由を説明するエラー メッセージインデックス作成が成功した場合は null です。</param>
        <param name="succeeded">キーによって識別されたドキュメントのインデックス作成操作が成功したかどうかを示す値です。</param>
        <param name="statusCode">インデックス作成操作のステータス コード。
            使用可能な値が含まれます: 正常な 200 を更新または削除を成功したドキュメントの作成、形式が正しくない入力ドキュメントのドキュメントが見つかりません、422 インデックスが一時的に利用可能な場合に、バージョンの競合の 409 404 の 400 201 または 503 タイミングについてサービスビジー状態です。</param>
        <summary>
            IndexingResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public string ErrorMessage { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingResult.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : string with get, set" Usage="Microsoft.Azure.Search.Models.IndexingResult.ErrorMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            キーによって識別されたドキュメントのインデックス作成操作が失敗した理由を説明するエラー メッセージを取得します。インデックス作成が成功した場合は null です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public string Key { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingResult.Key" />
      <MemberSignature Language="VB.NET" Value="Public Property Key As String" />
      <MemberSignature Language="F#" Value="member this.Key : string with get, set" Usage="Microsoft.Azure.Search.Models.IndexingResult.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="key")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            インデックス作成の要求では、ドキュメントのキーを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public int StatusCode { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingResult.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusCode As Integer" />
      <MemberSignature Language="F#" Value="member this.StatusCode : int with get, set" Usage="Microsoft.Azure.Search.Models.IndexingResult.StatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statusCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            インデックス作成操作のステータス コードを取得します。 使用可能な値が含まれます: 正常な 200 を更新または削除を成功したドキュメントの作成、形式が正しくない入力ドキュメントのドキュメントが見つかりません、422 インデックスが一時的に利用可能な場合に、バージョンの競合の 409 404 の 400 201 または 503 タイミングについてサービスビジー状態です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Succeeded">
      <MemberSignature Language="C#" Value="public bool Succeeded { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Succeeded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingResult.Succeeded" />
      <MemberSignature Language="VB.NET" Value="Public Property Succeeded As Boolean" />
      <MemberSignature Language="F#" Value="member this.Succeeded : bool with get, set" Usage="Microsoft.Azure.Search.Models.IndexingResult.Succeeded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            キーによって識別されたドキュメントのインデックス作成操作が成功したかどうかを示す値を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>