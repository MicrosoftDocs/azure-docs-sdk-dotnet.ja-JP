<Type Name="TableHttpRequestMessageExtensions" FullName="System.Net.Http.TableHttpRequestMessageExtensions">
  <TypeSignature Language="C#" Value="public static class TableHttpRequestMessageExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TableHttpRequestMessageExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Net.Http.TableHttpRequestMessageExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TableHttpRequestMessageExtensions" />
  <TypeSignature Language="F#" Value="type TableHttpRequestMessageExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            拡張メソッドを<see cref="T:System.Net.Http.HttpRequestMessage" />テーブルに関連する機能を提供するクラス<see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AreDeletedRowsRequested">
      <MemberSignature Language="C#" Value="public static bool AreDeletedRowsRequested (this System.Net.Http.HttpRequestMessage request);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool AreDeletedRowsRequested(class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.TableHttpRequestMessageExtensions.AreDeletedRowsRequested(System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function AreDeletedRowsRequested (request As HttpRequestMessage) As Boolean" />
      <MemberSignature Language="F#" Value="static member AreDeletedRowsRequested : System.Net.Http.HttpRequestMessage -&gt; bool" Usage="System.Net.Http.TableHttpRequestMessageExtensions.AreDeletedRowsRequested request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
      </Parameters>
      <Docs>
        <param name="request"><see cref="T:System.Net.Http.HttpRequestMessage" />要求</param>
        <summary>
            クライアントによって要求された行を削除するかどうかを判断します。
            </summary>
        <returns>True の場合は、削除された行は、要求された、それ以外の場合は False。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVersionFromIfMatch">
      <MemberSignature Language="C#" Value="public static byte[] GetVersionFromIfMatch (this System.Net.Http.HttpRequestMessage request);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig unsigned int8[] GetVersionFromIfMatch(class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.TableHttpRequestMessageExtensions.GetVersionFromIfMatch(System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetVersionFromIfMatch (request As HttpRequestMessage) As Byte()" />
      <MemberSignature Language="F#" Value="static member GetVersionFromIfMatch : System.Net.Http.HttpRequestMessage -&gt; byte[]" Usage="System.Net.Http.TableHttpRequestMessageExtensions.GetVersionFromIfMatch request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Reliability", "CA2000:Dispose objects before losing scope", Justification="Response is disposed by caller.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
      </Parameters>
      <Docs>
        <param name="request"></param>
        <summary>
            HTTP からテーブルの項目のバージョンを取得<c>IfMatch</c>ヘッダー。 場合、 <c>IfMatch</c>に無効な値が含まれています、<see cref="T:System.Web.Http.HttpResponseException" />がスローされます、<see cref="T:System.Net.Http.HttpResponseMessage" />ステータス コードで<see cref="F:System.Net.HttpStatusCode.BadRequest" />です。
            </summary>
        <returns>バージョンを表す有効なバージョンのバイト配列または<c>null</c> [なし] が存在していた場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSelectedProperties">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;string&gt; SetSelectedProperties (this System.Net.Http.HttpRequestMessage request, Type data, out bool isModified);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;string&gt; SetSelectedProperties(class System.Net.Http.HttpRequestMessage request, class System.Type data, [out] bool&amp; isModified) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.TableHttpRequestMessageExtensions.SetSelectedProperties(System.Net.Http.HttpRequestMessage,System.Type,System.Boolean@)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetSelectedProperties (request As HttpRequestMessage, data As Type, ByRef isModified As Boolean) As IList(Of String)" />
      <MemberSignature Language="F#" Value="static member SetSelectedProperties : System.Net.Http.HttpRequestMessage * Type *  -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="System.Net.Http.TableHttpRequestMessageExtensions.SetSelectedProperties (request, data, isModified)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", Justification="It's ok to have an out parameter here.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="data" Type="System.Type" />
        <Parameter Name="isModified" Type="System.Boolean&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="request"><see cref="T:System.Net.Http.HttpRequestMessage" />要求</param>
        <param name="data">データ モデルの型。</param>
        <param name="isModified">元の要求 URI の $select 句が操作されているかどうかどうかを示します。</param>
        <summary>
            実装する型の OData の $select クエリ オプションで含めるプロパティのセットを決定する、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" />インターフェイスです。 この関数は、選択したプロパティのセットを決定し、必要に応じて、要求の URI をそれに応じて更新します。
            </summary>
        <returns>選択されているプロパティのセットを実装する型の場合それ以外の場合は null。</returns>
        <remarks>クエリは実際には検証されません - この手順ではこれはの一部として実行、<see cref="T:System.Web.Http.QueryableAttribute" />検証します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSelectedProperties">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;string&gt; SetSelectedProperties (this System.Net.Http.HttpRequestMessage request, Type data, System.Collections.Generic.IDictionary&lt;string,string&gt; systemPropertyMap, out bool isModified);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;string&gt; SetSelectedProperties(class System.Net.Http.HttpRequestMessage request, class System.Type data, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; systemPropertyMap, [out] bool&amp; isModified) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.TableHttpRequestMessageExtensions.SetSelectedProperties(System.Net.Http.HttpRequestMessage,System.Type,System.Collections.Generic.IDictionary{System.String,System.String},System.Boolean@)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetSelectedProperties (request As HttpRequestMessage, data As Type, systemPropertyMap As IDictionary(Of String, String), ByRef isModified As Boolean) As IList(Of String)" />
      <MemberSignature Language="F#" Value="static member SetSelectedProperties : System.Net.Http.HttpRequestMessage * Type * System.Collections.Generic.IDictionary&lt;string, string&gt; *  -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="System.Net.Http.TableHttpRequestMessageExtensions.SetSelectedProperties (request, data, systemPropertyMap, isModified)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", Justification="It's ok to have an out parameter here.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="data" Type="System.Type" />
        <Parameter Name="systemPropertyMap" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="isModified" Type="System.Boolean&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="request"><see cref="T:System.Net.Http.HttpRequestMessage" />要求</param>
        <param name="data">データ モデルの型。</param>
        <param name="systemPropertyMap">システムのプロパティの代替名を指定する省略可能なマップします。</param>
        <param name="isModified">元の要求 URI の $select 句が操作されているかどうかどうかを示します。</param>
        <summary>
            実装する型の OData の $select クエリ オプションで含めるプロパティのセットを決定する、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" />インターフェイスです。 この関数は、選択したプロパティの組み合わせのセットを決定し、必要に応じて、要求の URI をそれに応じて更新します。
            </summary>
        <returns>選択されているプロパティのセットを実装する型の場合それ以外の場合は null。</returns>
        <remarks>クエリは実際には検証されません - この手順ではこれはの一部として実行、<see cref="T:System.Web.Http.QueryableAttribute" />検証します。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>