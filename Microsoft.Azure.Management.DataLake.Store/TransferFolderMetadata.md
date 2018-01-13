<Type Name="TransferFolderMetadata" FullName="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata">
  <TypeSignature Language="C#" Value="public class TransferFolderMetadata" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferFolderMetadata extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferFolderMetadata" />
  <TypeSignature Language="F#" Value="type TransferFolderMetadata = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.DebuggerDisplay("FileCount = {FileCount}, TransferId = {TransferId}, IsRecursive = {IsRecursive}")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            転送に関連する一般的なメタデータを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferFolderMetadata (string metadataFilePath, Microsoft.Azure.Management.DataLake.Store.TransferParameters transferParameters, Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter frontend);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string metadataFilePath, class Microsoft.Azure.Management.DataLake.Store.TransferParameters transferParameters, class Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter frontend) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.#ctor(System.String,Microsoft.Azure.Management.DataLake.Store.TransferParameters,Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata : string * Microsoft.Azure.Management.DataLake.Store.TransferParameters * Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter -&gt; Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata" Usage="new Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata (metadataFilePath, transferParameters, frontend)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="metadataFilePath" Type="System.String" />
        <Parameter Name="transferParameters" Type="Microsoft.Azure.Management.DataLake.Store.TransferParameters" />
        <Parameter Name="frontend" Type="Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter" />
      </Parameters>
      <Docs>
        <param name="metadataFilePath">このメタデータ ファイル (目的を保存) するために割り当てるファイルのパス。</param>
        <param name="transferParameters">このメタデータを構築するために使用するパラメーターです。</param>
        <param name="frontend">各ファイルのメタデータを生成するときに使用するフロント エンドです。</param>
        <summary>
            指定したパラメーターから新しい TransferFolderMetadata オブジェクトを構築します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteFile">
      <MemberSignature Language="C#" Value="public void DeleteFile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteFile() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.DeleteFile" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteFile ()" />
      <MemberSignature Language="F#" Value="member this.DeleteFile : unit -&gt; unit" Usage="transferFolderMetadata.DeleteFile " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            メタデータ ファイルをディスクから削除します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">Null または空の MetadataFilePath します。 このプロパティが設定されるまで、メタデータを削除することはできません。</exception>
      </Docs>
    </Member>
    <Member MemberName="FileCount">
      <MemberSignature Language="C#" Value="public int FileCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FileCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.FileCount" />
      <MemberSignature Language="VB.NET" Value="Public Property FileCount As Integer" />
      <MemberSignature Language="F#" Value="member this.FileCount : int with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.FileCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="FileCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または転送でこのファイルの数を示す値を設定します。
            </summary>
        <value>
            セグメントの数。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Files">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.TransferMetadata[] Files { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Store.TransferMetadata[] Files" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.Files" />
      <MemberSignature Language="VB.NET" Value="Public Property Files As TransferMetadata()" />
      <MemberSignature Language="F#" Value="member this.Files : Microsoft.Azure.Management.DataLake.Store.TransferMetadata[] with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.Files" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Files")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.TransferMetadata[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ファイル転送のメタデータの配列へのポインターを取得します。 これは、各ファイルの転送中に使用されます。
            </summary>
        <value>
            セグメント。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InputFolderPath">
      <MemberSignature Language="C#" Value="public string InputFolderPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InputFolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.InputFolderPath" />
      <MemberSignature Language="VB.NET" Value="Public Property InputFolderPath As String" />
      <MemberSignature Language="F#" Value="member this.InputFolderPath : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.InputFolderPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="InputFolderPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または転送するファイルへの完全パスを示す値を設定します。
            </summary>
        <value>
            入力ファイルのパス。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRecursive">
      <MemberSignature Language="C#" Value="public bool IsRecursive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRecursive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.IsRecursive" />
      <MemberSignature Language="VB.NET" Value="Public Property IsRecursive As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRecursive : bool with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.IsRecursive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="IsRecursive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            フラットなディレクトリの転送や recurisve ディレクトリの転送であるかどうかを示す値を取得します。
            </summary>
        <value>
          <c>true</c>場合、このインスタンスが再帰的です。 それ以外の場合、 <c>false</c>です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Save">
      <MemberSignature Language="C#" Value="public void Save ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Save() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.Save" />
      <MemberSignature Language="VB.NET" Value="Public Sub Save ()" />
      <MemberSignature Language="F#" Value="member this.Save : unit -&gt; unit" Usage="transferFolderMetadata.Save " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            指定したメタデータを標準的な場所に保存します。 このメソッドは、スレッド セーフです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetStreamFolderPath">
      <MemberSignature Language="C#" Value="public string TargetStreamFolderPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetStreamFolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TargetStreamFolderPath" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetStreamFolderPath As String" />
      <MemberSignature Language="F#" Value="member this.TargetStreamFolderPath : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TargetStreamFolderPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="TargetStreamFolderPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはファイルとフォルダーが転送されるすべてのルート フォルダーとして使用されるストリーム全体のフォルダーのパスを示す値を設定します。
            </summary>
        <value>
            ターゲット ストリーム パス。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalFileBytes">
      <MemberSignature Language="C#" Value="public long TotalFileBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalFileBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TotalFileBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalFileBytes As Long" />
      <MemberSignature Language="F#" Value="member this.TotalFileBytes : int64 with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TotalFileBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="TotalFileBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはすべてのファイルの合計バイト数を設定します。
            </summary>
        <value>
            すべてのファイルの合計バイト数。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferId">
      <MemberSignature Language="C#" Value="public string TransferId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TransferId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TransferId" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferId As String" />
      <MemberSignature Language="F#" Value="member this.TransferId : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TransferId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="TransferId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこの譲渡に関連付けられている一意の識別子を示す値を設定します。
            </summary>
        <value>
            転送の識別子です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>