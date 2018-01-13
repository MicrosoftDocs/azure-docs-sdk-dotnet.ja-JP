<Type Name="LinkedCrs" FullName="Microsoft.Azure.Documents.Spatial.LinkedCrs">
  <TypeSignature Language="C#" Value="public sealed class LinkedCrs : Microsoft.Azure.Documents.Spatial.Crs, IEquatable&lt;Microsoft.Azure.Documents.Spatial.LinkedCrs&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit LinkedCrs extends Microsoft.Azure.Documents.Spatial.Crs implements class System.IEquatable`1&lt;class Microsoft.Azure.Documents.Spatial.LinkedCrs&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class LinkedCrs&#xA;Inherits Crs&#xA;Implements IEquatable(Of LinkedCrs)" />
  <TypeSignature Language="F#" Value="type LinkedCrs = class&#xA;    inherit Crs&#xA;    interface IEquatable&lt;LinkedCrs&gt;" />
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
    <BaseTypeName>Microsoft.Azure.Documents.Spatial.Crs</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Documents.Spatial.LinkedCrs&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Azure Cosmos DB サービスのリンクで識別される参照システムを調整します。 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Documents.Spatial.LinkedCrs other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Documents.Spatial.LinkedCrs other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.LinkedCrs.Equals(Microsoft.Azure.Documents.Spatial.LinkedCrs)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As LinkedCrs) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Documents.Spatial.LinkedCrs -&gt; bool" Usage="linkedCrs.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Spatial.LinkedCrs" />
      </Parameters>
      <Docs>
        <param name="other">
          <see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" />これと比較する<see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" />です。</param>
        <summary>
            かどうかをこの<see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" />と等しい<paramref name="other" />Cosmos DB の Azure サービスにします。 
            </summary>
        <returns>
          <c>true</c> CRSs が等しい場合は。 <c>false</c>それ以外の場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.LinkedCrs.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="linkedCrs.Equals obj" />
      <MemberType>Method</MemberType>
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">現在のオブジェクトと比較するオブジェクト。 </param>
        <summary>
            決定するかどうか、指定した<see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" />が現在と等しい<see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" />Cosmos DB の Azure サービスで。 
            </summary>
        <returns>
            指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.LinkedCrs.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="linkedCrs.GetHashCode " />
      <MemberType>Method</MemberType>
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
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ハッシュ関数として機能<see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" />Cosmos DB の Azure サービスにします。 
            </summary>
        <returns>
            現在の <see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" /> のハッシュ コード。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Href">
      <MemberSignature Language="C#" Value="public string Href { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Href" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.LinkedCrs.Href" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Href As String" />
      <MemberSignature Language="F#" Value="member this.Href : string" Usage="Microsoft.Azure.Documents.Spatial.LinkedCrs.Href" />
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
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Cosmos DB の Azure サービスで調整参照システムを識別するリンクを取得します。 
            </summary>
        <value>
            調整参照システムを識別するリンクです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HrefType">
      <MemberSignature Language="C#" Value="public string HrefType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HrefType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.LinkedCrs.HrefType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HrefType As String" />
      <MemberSignature Language="F#" Value="member this.HrefType : string" Usage="Microsoft.Azure.Documents.Spatial.LinkedCrs.HrefType" />
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
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            指定された CRS パラメーターを表すために使用される形式にするヒントの省略可能な文字列を取得<see cref="P:Microsoft.Azure.Documents.Spatial.LinkedCrs.Href" />Cosmos DB の Azure サービスにします。 
            </summary>
        <value>
            ヒントで指定された CRS パラメーターを表すために使用される形式にする省略可能な文字列<see cref="P:Microsoft.Azure.Documents.Spatial.LinkedCrs.Href" />です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>