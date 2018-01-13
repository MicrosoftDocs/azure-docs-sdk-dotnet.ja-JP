<Type Name="TableHttpWebRequestFactory" FullName="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory">
  <TypeSignature Language="C#" Value="public static class TableHttpWebRequestFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TableHttpWebRequestFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class TableHttpWebRequestFactory" />
  <TypeSignature Language="F#" Value="type TableHttpWebRequestFactory = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            テーブル サービスでテーブルを管理する web 要求を構築するためのファクトリ クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Microsoft.Azure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, class Microsoft.Azure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.GetAcl(System.Uri,Microsoft.Azure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Microsoft.Azure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.Azure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.GetAcl (uri, builder, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.Azure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />テーブルの絶対 URI を指定します。</param>
        <param name="builder">A <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="operationContext"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルの ACL を返す web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Microsoft.Azure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, class Microsoft.Azure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.GetAcl(System.Uri,Microsoft.Azure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},System.Boolean,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Microsoft.Azure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * bool * Microsoft.Azure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.GetAcl (uri, builder, timeout, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.Azure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />テーブルの絶対 URI を指定します。</param>
        <param name="builder">A <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルの ACL を返す web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceProperties (Uri uri, Microsoft.Azure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceProperties(class System.Uri uri, class Microsoft.Azure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.GetServiceProperties(System.Uri,Microsoft.Azure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceProperties : Uri * Microsoft.Azure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.Azure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.GetServiceProperties (uri, builder, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.Azure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />テーブル サービスのエンドポイントを指定します。</param>
        <param name="builder">A <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="operationContext"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブル サービスのプロパティを取得する web 要求を作成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStats">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceStats (Uri uri, Microsoft.Azure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceStats(class System.Uri uri, class Microsoft.Azure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.GetServiceStats(System.Uri,Microsoft.Azure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceStats : Uri * Microsoft.Azure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.Azure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.GetServiceStats (uri, builder, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.Azure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />テーブル サービスのエンドポイントを指定します。</param>
        <param name="builder">A <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="operationContext"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブル サービスの統計情報を取得する web 要求を作成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Microsoft.Azure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, class Microsoft.Azure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.SetAcl(System.Uri,Microsoft.Azure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Microsoft.Azure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.Azure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.SetAcl (uri, builder, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.Azure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />テーブルの絶対 URI を指定します。</param>
        <param name="builder">A <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="operationContext"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルの ACL を設定する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Microsoft.Azure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, class Microsoft.Azure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.SetAcl(System.Uri,Microsoft.Azure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},System.Boolean,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Microsoft.Azure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * bool * Microsoft.Azure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.SetAcl (uri, builder, timeout, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.Azure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />テーブルの絶対 URI を指定します。</param>
        <param name="builder">A <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルの ACL を設定する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetServiceProperties (Uri uri, Microsoft.Azure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetServiceProperties(class System.Uri uri, class Microsoft.Azure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.SetServiceProperties(System.Uri,Microsoft.Azure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetServiceProperties : Uri * Microsoft.Azure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.Azure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.SetServiceProperties (uri, builder, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.Azure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />テーブル サービスのエンドポイントを指定します。</param>
        <param name="builder">A <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="operationContext"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブル サービスのプロパティを設定する web 要求を作成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteServiceProperties">
      <MemberSignature Language="C#" Value="public static void WriteServiceProperties (Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, System.IO.Stream outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void WriteServiceProperties(class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, class System.IO.Stream outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.WriteServiceProperties(Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub WriteServiceProperties (properties As ServiceProperties, outputStream As Stream)" />
      <MemberSignature Language="F#" Value="static member WriteServiceProperties : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * System.IO.Stream -&gt; unit" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.WriteServiceProperties (properties, outputStream)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="outputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="properties">A<see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />を書式設定し、ストリームに書き込むサービス プロパティを含むオブジェクト。</param>
        <param name="outputStream"><see cref="T:System.IO.Stream" />書式設定されたプロパティが書き込まれるオブジェクト。</param>
        <summary>
            テーブル サービス プロパティを XML 形式で、ストリームに書き込みます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>