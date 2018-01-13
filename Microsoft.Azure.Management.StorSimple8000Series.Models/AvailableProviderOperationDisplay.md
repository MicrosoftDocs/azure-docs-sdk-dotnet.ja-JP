<Type Name="AvailableProviderOperationDisplay" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay">
  <TypeSignature Language="C#" Value="public class AvailableProviderOperationDisplay" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AvailableProviderOperationDisplay extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay" />
  <TypeSignature Language="VB.NET" Value="Public Class AvailableProviderOperationDisplay" />
  <TypeSignature Language="F#" Value="type AvailableProviderOperationDisplay = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            この特定の操作/アクションのローカライズされた表示情報が含まれています。 これらの値は、(a) は、カスタムのロールの定義では、RBAC イベント サービスと (c) 監査履歴/レコードの管理操作用の (b) 複雑なクエリ フィルターの複数のクライアントによって使用されます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailableProviderOperationDisplay ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AvailableProviderOperationDisplay クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailableProviderOperationDisplay (string provider = null, string resource = null, string operation = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string provider, string resource, string operation, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional provider As String = null, Optional resource As String = null, Optional operation As String = null, Optional description As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay : string * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay (provider, resource, operation, description)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="provider">ローカライズされた表示形式、リソース プロバイダー名前のことが期待されても、パブリッシャー/担当会社が含まれます。 タイトルの大文字と小文字を使用して、ファースト パーティのサービスの 'Microsoft' で始まるし、必要があります。</param>
        <param name="resource">このアクション/操作 - に関連するリソースの種類のローカライズされた表示形式にリソース プロバイダーのパブリックのドキュメントを一致する必要があります。 タイトルの大文字と小文字を使用する必要があります。
            - 例については、'name' セクションを参照してください。</param>
        <param name="operation">操作のローカライズされた表示名は、ユーザーに表示する必要があります。 (ドロップダウン リストに収まる) に簡潔なが (つまり自己文書化) がオフになります。 タイトルの大文字と小文字を使用し、それを適用するエンティティ/リソースを含めるか。</param>
        <param name="description">操作のローカライズされたわかりやすい説明は、ユーザーを表示する必要があります。 で包括的なことがまだ簡潔なのツール ヒントで使用され、詳細なビューです。</param>
        <summary>
            AvailableProviderOperationDisplay クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはユーザーに表示するか、操作のローカライズされたわかりやすい説明を設定します。 で包括的なことがまだ簡潔なのツール ヒントで使用され、詳細なビューです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public string Operation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Operation" />
      <MemberSignature Language="VB.NET" Value="Public Property Operation As String" />
      <MemberSignature Language="F#" Value="member this.Operation : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Operation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはユーザーに表示するか、操作のローカライズされた表示名を設定します。 (ドロップダウン リストに収まる) に簡潔なが (つまり自己文書化) がオフになります。 タイトルの大文字と小文字を使用し、それを適用するエンティティ/リソースを含めるか。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public string Provider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Provider" />
      <MemberSignature Language="VB.NET" Value="Public Property Provider As String" />
      <MemberSignature Language="F#" Value="member this.Provider : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはローカライズされた表示形式を設定、リソース プロバイダー名前のことが期待されても、パブリッシャー/担当会社が含まれます。 タイトルの大文字と小文字を使用して、ファースト パーティのサービスの 'Microsoft' で始まるし、必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resource">
      <MemberSignature Language="C#" Value="public string Resource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Resource" />
      <MemberSignature Language="VB.NET" Value="Public Property Resource As String" />
      <MemberSignature Language="F#" Value="member this.Resource : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Resource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このアクション/操作 - に関連するリソースの種類のローカライズされた表示形式を取得または設定は、リソース プロバイダーのパブリックのドキュメントに一致する必要があります。 タイトルの大文字と小文字を使用する必要があります。
            - 例については、'name' セクションを参照してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>