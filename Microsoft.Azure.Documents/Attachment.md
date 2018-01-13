<Type Name="Attachment" FullName="Microsoft.Azure.Documents.Attachment">
  <TypeSignature Language="C#" Value="public class Attachment : Microsoft.Azure.Documents.Resource, System.Dynamic.IDynamicMetaObjectProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Attachment extends Microsoft.Azure.Documents.Resource implements class System.Dynamic.IDynamicMetaObjectProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Attachment" />
  <TypeSignature Language="VB.NET" Value="Public Class Attachment&#xA;Inherits Resource&#xA;Implements IDynamicMetaObjectProvider" />
  <TypeSignature Language="F#" Value="type Attachment = class&#xA;    inherit Resource&#xA;    interface IDynamicMetaObjectProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Dynamic.IDynamicMetaObjectProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Azure Cosmos DB サービスのドキュメントの添付ファイルを表します。
            </summary>
    <remarks>
            各ドキュメントには、イメージ、バイナリまたはラージ テキスト blob などの任意の形式のデータを含む 0 個以上の添付ファイルを含めることがあります。 添付ファイルのクラスでは、その場所と MIME コンテンツ タイプのように、添付ファイルに関する情報を格納するために使用する Azure Cosmos DB リソースを表します。 ペイロード (「メディア」) 自体は MediaLink プロパティを通じて参照されます。 添付ファイル クラスは、DynamicObject であり、永続化するカスタム メタデータを含めることができます。 
            
            管理対象として、添付ファイルを作成できると管理対象外です。 Azure Cosmos DB を介して管理対象として、添付ファイルが作成する場合、システムによって生成される mediaLink を割り当てられます。 Azure Cosmos DB し、自動的にガベージ コレクションが実行メディアの親ドキュメントを削除するとします。
            
            MediaLink プロパティなど、外部の場所を格納するファイル共有または Azure Blob ストレージ URI を再利用することができます。 Cosmos の azure DB では、外部の場所の mediaLinks でガベージ コレクションは実行しません。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Attachment ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Attachment.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Attachment" /> Azure Cosmos DB サービスのクラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Attachment.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.Documents.Attachment.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="contentType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスの添付ファイルの MIME コンテンツ タイプを設定します。
            </summary>
        <value>
            添付ファイルの MIME コンテンツ タイプ。
            </value>
        <remarks>たとえば、「テキスト/プレーン」for text files"イメージ/jpeg"イメージを設定します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="MediaLink">
      <MemberSignature Language="C#" Value="public string MediaLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MediaLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Attachment.MediaLink" />
      <MemberSignature Language="VB.NET" Value="Public Property MediaLink As String" />
      <MemberSignature Language="F#" Value="member this.MediaLink : string with get, set" Usage="Microsoft.Azure.Documents.Attachment.MediaLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="media")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスの添付ファイルのコンテンツに関連付けられたメディア リンクを設定します。
            </summary>
        <value>
            添付ファイルのコンテンツに関連付けられたメディア リンクします。
            </value>
        <remarks>Azure の Cosmos DB では、マネージ コードとアンマネージの両方の添付ファイルをサポートします。</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject">
      <MemberSignature Language="C#" Value="System.Dynamic.DynamicMetaObject IDynamicMetaObjectProvider.GetMetaObject (System.Linq.Expressions.Expression parameter);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Dynamic.DynamicMetaObject System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject(class System.Linq.Expressions.Expression parameter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Attachment.System#Dynamic#IDynamicMetaObjectProvider#GetMetaObject(System.Linq.Expressions.Expression)" />
      <MemberSignature Language="VB.NET" Value="Function GetMetaObject (parameter As Expression) As DynamicMetaObject Implements IDynamicMetaObjectProvider.GetMetaObject" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject(System.Linq.Expressions.Expression)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Dynamic.DynamicMetaObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameter" Type="System.Linq.Expressions.Expression" />
      </Parameters>
      <Docs>
        <param name="parameter">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>