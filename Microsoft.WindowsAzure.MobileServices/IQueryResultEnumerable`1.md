<Type Name="IQueryResultEnumerable&lt;T&gt;" FullName="Microsoft.WindowsAzure.MobileServices.IQueryResultEnumerable&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IQueryResultEnumerable&lt;out T&gt; : System.Collections.Generic.IEnumerable&lt;out T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IQueryResultEnumerable`1&lt;+ T&gt; implements class System.Collections.Generic.IEnumerable`1&lt;!T&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.IQueryResultEnumerable`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IQueryResultEnumerable(Of Out T)&#xA;Implements IEnumerable(Of Out T)" />
  <TypeSignature Language="F#" Value="type IQueryResultEnumerable&lt;'T&gt; = interface&#xA;    interface seq&lt;'T&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>Covariant</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;T&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>
            IQueryResultEnumerable {t} インターフェイスは、余分な詳細と共に返される応答例: 合計数と次のリンクを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="NextLink">
      <MemberSignature Language="C#" Value="public string NextLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IQueryResultEnumerable`1.NextLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextLink As String" />
      <MemberSignature Language="F#" Value="member this.NextLink : string" Usage="Microsoft.WindowsAzure.MobileServices.IQueryResultEnumerable&lt;'T&gt;.NextLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            応答ヘッダーで返される結果の次のページへのリンクを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IQueryResultEnumerable`1.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="Microsoft.WindowsAzure.MobileServices.IQueryResultEnumerable&lt;'T&gt;.TotalCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クライアントまたはサーバーで指定された任意の take paging/limit 句を無視して返されたすべてのレコードの合計数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>