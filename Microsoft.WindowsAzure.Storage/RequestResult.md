<Type Name="RequestResult" FullName="Microsoft.WindowsAzure.Storage.RequestResult">
  <TypeSignature Language="C#" Value="public sealed class RequestResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit RequestResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.RequestResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RequestResult" />
  <TypeSignature Language="F#" Value="type RequestResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            物理的な要求の結果を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RequestResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentMd5">
      <MemberSignature Language="C#" Value="public string ContentMd5 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentMd5" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.ContentMd5" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContentMd5 As String" />
      <MemberSignature Language="F#" Value="member this.ContentMd5 : string" Usage="Microsoft.WindowsAzure.Storage.RequestResult.ContentMd5" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求の content-md5 値を取得します。 
            </summary>
        <value>要求の content-md5 値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EgressBytes">
      <MemberSignature Language="C#" Value="public long EgressBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 EgressBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.EgressBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property EgressBytes As Long" />
      <MemberSignature Language="F#" Value="member this.EgressBytes : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.RequestResult.EgressBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>        
            指定された要求の要求本文に書き込まれたバイト数
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public DateTime EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.EndTime : DateTime" Usage="Microsoft.WindowsAzure.Storage.RequestResult.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作の終了時刻を取得します。
            </summary>
        <value>A<see cref="T:System.DateTime" />操作の終了時刻を示す値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.WindowsAzure.Storage.RequestResult.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求の ETag 値を取得します。
            </summary>
        <value>要求の ETag 値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.Exception" />
      <MemberSignature Language="VB.NET" Value="Public Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception with get, set" Usage="Microsoft.WindowsAzure.Storage.RequestResult.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定するとします。
            </summary>
        <value><see cref="T:System.Exception" /> オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedErrorInformation">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation ExtendedErrorInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation ExtendedErrorInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.ExtendedErrorInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExtendedErrorInformation As StorageExtendedErrorInformation" />
      <MemberSignature Language="F#" Value="member this.ExtendedErrorInformation : Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation" Usage="Microsoft.WindowsAzure.Storage.RequestResult.ExtendedErrorInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            拡張エラー情報を取得します。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation" /> オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpStatusCode">
      <MemberSignature Language="C#" Value="public int HttpStatusCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HttpStatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.HttpStatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpStatusCode As Integer" />
      <MemberSignature Language="F#" Value="member this.HttpStatusCode : int with get, set" Usage="Microsoft.WindowsAzure.Storage.RequestResult.HttpStatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または要求の HTTP ステータス コードを設定します。
            </summary>
        <value>要求の HTTP ステータス コード。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpStatusMessage">
      <MemberSignature Language="C#" Value="public string HttpStatusMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HttpStatusMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.HttpStatusMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HttpStatusMessage As String" />
      <MemberSignature Language="F#" Value="member this.HttpStatusMessage : string" Usage="Microsoft.WindowsAzure.Storage.RequestResult.HttpStatusMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求の HTTP ステータス メッセージを取得します。
            </summary>
        <value>要求の HTTP ステータス メッセージ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IngressBytes">
      <MemberSignature Language="C#" Value="public long IngressBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 IngressBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.IngressBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property IngressBytes As Long" />
      <MemberSignature Language="F#" Value="member this.IngressBytes : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.RequestResult.IngressBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            指定された要求の応答の本体から読み取られたバイト数
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRequestServerEncrypted">
      <MemberSignature Language="C#" Value="public bool IsRequestServerEncrypted { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRequestServerEncrypted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.IsRequestServerEncrypted" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsRequestServerEncrypted As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRequestServerEncrypted : bool" Usage="Microsoft.WindowsAzure.Storage.RequestResult.IsRequestServerEncrypted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            書き込み操作のデータがサーバー側で暗号化されたかどうかを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadXml">
      <MemberSignature Language="C#" Value="public void ReadXml (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ReadXml(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RequestResult.ReadXml(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReadXml (reader As XmlReader)" />
      <MemberSignature Language="F#" Value="member this.ReadXml : System.Xml.XmlReader -&gt; unit" Usage="requestResult.ReadXml reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader"><see cref="T:System.Xml.XmlReader" /> RequestResult が逆シリアル化するストリームします。</param>
        <summary>
            XML 表現からシリアル化可能な RequestResult を生成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestDate">
      <MemberSignature Language="C#" Value="public string RequestDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.RequestDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestDate As String" />
      <MemberSignature Language="F#" Value="member this.RequestDate : string" Usage="Microsoft.WindowsAzure.Storage.RequestResult.RequestDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求の日付を取得します。
            </summary>
        <value>要求の日付。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceRequestID">
      <MemberSignature Language="C#" Value="public string ServiceRequestID { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceRequestID" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.ServiceRequestID" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceRequestID As String" />
      <MemberSignature Language="F#" Value="member this.ServiceRequestID : string" Usage="Microsoft.WindowsAzure.Storage.RequestResult.ServiceRequestID" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この要求のサービス要求 ID を取得します。
            </summary>
        <value>この要求のサービス要求 ID。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.WindowsAzure.Storage.RequestResult.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作の開始時刻を取得します。
            </summary>
        <value>A<see cref="T:System.DateTime" />操作の開始時刻を示す値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLocation">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageLocation TargetLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.StorageLocation TargetLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.TargetLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetLocation As StorageLocation" />
      <MemberSignature Language="F#" Value="member this.TargetLocation : Microsoft.WindowsAzure.Storage.StorageLocation" Usage="Microsoft.WindowsAzure.Storage.RequestResult.TargetLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageLocation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求の送信先の場所を取得します。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> 列挙値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TranslateFromExceptionMessage">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.RequestResult TranslateFromExceptionMessage (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.RequestResult TranslateFromExceptionMessage(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RequestResult.TranslateFromExceptionMessage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TranslateFromExceptionMessage (message As String) As RequestResult" />
      <MemberSignature Language="F#" Value="static member TranslateFromExceptionMessage : string -&gt; Microsoft.WindowsAzure.Storage.RequestResult" Usage="Microsoft.WindowsAzure.Storage.RequestResult.TranslateFromExceptionMessage message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This should be available only in Microsoft.WindowsAzure.Storage.WinMD and not in Microsoft.WindowsAzure.Storage.dll. Please use ReadXML to deserialize RequestResult when Microsoft.WindowsAzure.Storage.dll is used.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RequestResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">変換するメッセージ。</param>
        <summary>
            指定されたメッセージの変換、<see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" />オブジェクト。
            </summary>
        <returns>翻訳された<see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteXml">
      <MemberSignature Language="C#" Value="public void WriteXml (System.Xml.XmlWriter writer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void WriteXml(class System.Xml.XmlWriter writer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RequestResult.WriteXml(System.Xml.XmlWriter)" />
      <MemberSignature Language="VB.NET" Value="Public Sub WriteXml (writer As XmlWriter)" />
      <MemberSignature Language="F#" Value="member this.WriteXml : System.Xml.XmlWriter -&gt; unit" Usage="requestResult.WriteXml writer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
      </Parameters>
      <Docs>
        <param name="writer"><see cref="T:System.Xml.XmlWriter" /> RequestResult のシリアル化ストリームします。</param>
        <summary>
            シリアル化可能な RequestResult を XML 表現に変換します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>