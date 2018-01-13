<Type Name="TableHttpWebResponseParsers" FullName="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers">
  <TypeSignature Language="C#" Value="public static class TableHttpWebResponseParsers" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TableHttpWebResponseParsers extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers" />
  <TypeSignature Language="VB.NET" Value="Public Class TableHttpWebResponseParsers" />
  <TypeSignature Language="F#" Value="type TableHttpWebResponseParsers = class" />
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
            テーブル サービスから応答ストリームを解析するためのメソッドのセットを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetRequestId">
      <MemberSignature Language="C#" Value="public static string GetRequestId (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetRequestId(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers.GetRequestId(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetRequestId (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetRequestId : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers.GetRequestId response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response">Web 応答です。</param>
        <summary>
            応答からの要求 ID を取得します。
            </summary>
        <returns>要求に関連付けられている一意の値。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadServiceProperties">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties ReadServiceProperties (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties ReadServiceProperties(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers.ReadServiceProperties(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadServiceProperties (inputStream As Stream) As ServiceProperties" />
      <MemberSignature Language="F#" Value="static member ReadServiceProperties : System.IO.Stream -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers.ReadServiceProperties inputStream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="inputStream">サービスのプロパティが読み取り元のストリーム。</param>
        <summary>
            サービスのプロパティをストリームから読み取ります。
            </summary>
        <returns>ストリームに格納されているサービスのプロパティです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadServiceStats">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Storage.Shared.Protocol.ServiceStats ReadServiceStats (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Storage.Shared.Protocol.ServiceStats ReadServiceStats(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers.ReadServiceStats(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadServiceStats (inputStream As Stream) As ServiceStats" />
      <MemberSignature Language="F#" Value="static member ReadServiceStats : System.IO.Stream -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers.ReadServiceStats inputStream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.Shared.Protocol.ServiceStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="inputStream">サービスの統計情報を読み取り元のストリーム。</param>
        <summary>
            ストリームからサービスの統計情報を読み取ります。
            </summary>
        <returns>ストリームに格納されているサービスの統計情報です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadSharedAccessIdentifiers">
      <MemberSignature Language="C#" Value="public static void ReadSharedAccessIdentifiers (System.IO.Stream inputStream, Microsoft.Azure.CosmosDB.Table.TablePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ReadSharedAccessIdentifiers(class System.IO.Stream inputStream, class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers.ReadSharedAccessIdentifiers(System.IO.Stream,Microsoft.Azure.CosmosDB.Table.TablePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ReadSharedAccessIdentifiers (inputStream As Stream, permissions As TablePermissions)" />
      <MemberSignature Language="F#" Value="static member ReadSharedAccessIdentifiers : System.IO.Stream * Microsoft.Azure.CosmosDB.Table.TablePermissions -&gt; unit" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers.ReadSharedAccessIdentifiers (inputStream, permissions)" />
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
        <Parameter Name="inputStream" Type="System.IO.Stream" />
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
      </Parameters>
      <Docs>
        <param name="inputStream">Xml 形式のポリシーのストリーム。</param>
        <param name="permissions">ポリシーが書き込まれるアクセス許可オブジェクト。</param>
        <summary>
            共有アクセス ポリシーを xml ストリームから読み取ります。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>