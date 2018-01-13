<Type Name="TableResult" FullName="Microsoft.Azure.CosmosDB.Table.TableResult">
  <TypeSignature Language="C#" Value="public sealed class TableResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TableResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TableResult" />
  <TypeSignature Language="F#" Value="type TableResult = class" />
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
            テーブル操作の結果を表します。
            </summary>
    <remarks><see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" />クラスは、HTTP 応答と、特定の返されるすべてのエンティティをカプセル化<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />です。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableResult.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableResult.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定と共に返される ETag、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />結果を要求します。
            </summary>
        <value>返される ETag、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />結果を要求します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpStatusCode">
      <MemberSignature Language="C#" Value="public int HttpStatusCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HttpStatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableResult.HttpStatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpStatusCode As Integer" />
      <MemberSignature Language="F#" Value="member this.HttpStatusCode : int with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableResult.HttpStatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定によって返される HTTP ステータス コード、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />要求します。
            </summary>
        <value>によって返される HTTP ステータス コード、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />要求します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public object Result { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableResult.Result" />
      <MemberSignature Language="VB.NET" Value="Public Property Result As Object" />
      <MemberSignature Language="F#" Value="member this.Result : obj with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableResult.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            によって返される結果取得または設定、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />として、<see cref="T:System.Object" />です。
            </summary>
        <value>として、テーブル操作の結果、<see cref="T:System.Object" />です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableResult.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string" Usage="Microsoft.Azure.CosmosDB.Table.TableResult.SessionToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            返されたセッション トークンの取得、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />結果を要求します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>