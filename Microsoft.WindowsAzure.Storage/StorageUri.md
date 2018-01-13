<Type Name="StorageUri" FullName="Microsoft.WindowsAzure.Storage.StorageUri">
  <TypeSignature Language="C#" Value="public sealed class StorageUri : IEquatable&lt;Microsoft.WindowsAzure.Storage.StorageUri&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StorageUri extends System.Object implements class System.IEquatable`1&lt;class Microsoft.WindowsAzure.Storage.StorageUri&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.StorageUri" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StorageUri&#xA;Implements IEquatable(Of StorageUri)" />
  <TypeSignature Language="F#" Value="type StorageUri = class&#xA;    interface IEquatable&lt;StorageUri&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.WindowsAzure.Storage.StorageUri&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Microsoft Azure ストレージ リソースのプライマリとセカンダリの場所の Uri が含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageUri (Uri primaryUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri primaryUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (primaryUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.StorageUri : Uri -&gt; Microsoft.WindowsAzure.Storage.StorageUri" Usage="new Microsoft.WindowsAzure.Storage.StorageUri primaryUri" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="primaryUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="primaryUri"><see cref="T:System.Uri" />プライマリ エンドポイント。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />クラス、ストレージ アカウントのプライマリ エンドポイントを使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageUri (Uri primaryUri, Uri secondaryUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri primaryUri, class System.Uri secondaryUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.#ctor(System.Uri,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (primaryUri As Uri, secondaryUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.StorageUri : Uri * Uri -&gt; Microsoft.WindowsAzure.Storage.StorageUri" Usage="new Microsoft.WindowsAzure.Storage.StorageUri (primaryUri, secondaryUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="primaryUri" Type="System.Uri" />
        <Parameter Name="secondaryUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="primaryUri"><see cref="T:System.Uri" />プライマリ エンドポイント。</param>
        <param name="secondaryUri"><see cref="T:System.Uri" />拠点のエンドポイントにします。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />クラス、ストレージ アカウントのプライマリとセカンダリ エンドポイントを使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.WindowsAzure.Storage.StorageUri other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.WindowsAzure.Storage.StorageUri other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.Equals(Microsoft.WindowsAzure.Storage.StorageUri)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As StorageUri) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.WindowsAzure.Storage.StorageUri -&gt; bool" Usage="storageUri.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
      </Parameters>
      <Docs>
        <param name="other">このオブジェクトと比較するオブジェクト。</param>
        <summary>
            現在のオブジェクトが、同じ型の別のオブジェクトと等しいかどうかを示します。
            </summary>
        <returns>
          <c>true</c>現在のオブジェクトが等しい場合、<paramref name="other" />パラメーターです。 それ以外の場合、 <c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="storageUri.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">このインスタンスと比較する <see cref="T:System.Object" />。</param>
        <summary>
            指定した <see cref="T:System.Object" /> がこのインスタンスと等しいかどうかを判定します。
            </summary>
        <returns>
          <c>true</c>場合、指定した<see cref="T:System.Object" />、それ以外のこのインスタンスと等しい<c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="storageUri.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            このインスタンスのハッシュ コードを返します。
            </summary>
        <returns>
            このインスタンスのハッシュ コード。ハッシュ アルゴリズムでもハッシュ テーブルのようなデータ構造でも使用できるもの。 
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetUri">
      <MemberSignature Language="C#" Value="public Uri GetUri (Microsoft.WindowsAzure.Storage.StorageLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Uri GetUri(valuetype Microsoft.WindowsAzure.Storage.StorageLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.GetUri(Microsoft.WindowsAzure.Storage.StorageLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetUri (location As StorageLocation) As Uri" />
      <MemberSignature Language="F#" Value="member this.GetUri : Microsoft.WindowsAzure.Storage.StorageLocation -&gt; Uri" Usage="storageUri.GetUri location" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.WindowsAzure.Storage.StorageLocation" />
      </Parameters>
      <Docs>
        <param name="location"><see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> 列挙値。</param>
        <summary>
            指定した場所にストレージ アカウントのエンドポイントの URI を返します。
            </summary>
        <returns><see cref="T:System.Uri" />のエンドポイントの指定された場所。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (Microsoft.WindowsAzure.Storage.StorageUri uri1, Microsoft.WindowsAzure.Storage.StorageUri uri2);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(class Microsoft.WindowsAzure.Storage.StorageUri uri1, class Microsoft.WindowsAzure.Storage.StorageUri uri2) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.op_Equality(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.StorageUri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (uri1 As StorageUri, uri2 As StorageUri) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.StorageUri -&gt; bool" Usage="uri1 = uri2" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri1" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="uri2" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
      </Parameters>
      <Docs>
        <param name="uri1">比較する最初の <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> オブジェクト。</param>
        <param name="uri2">比較する 2 番目の <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> オブジェクト。</param>
        <summary>
            比較する 2 つ<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />の等価のオブジェクト。
            </summary>
        <returns>
          <c>true</c>場合、<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />オブジェクトと等価の値がある、それ以外の<c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (Microsoft.WindowsAzure.Storage.StorageUri uri1, Microsoft.WindowsAzure.Storage.StorageUri uri2);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(class Microsoft.WindowsAzure.Storage.StorageUri uri1, class Microsoft.WindowsAzure.Storage.StorageUri uri2) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.op_Inequality(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.StorageUri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (uri1 As StorageUri, uri2 As StorageUri) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.StorageUri -&gt; bool" Usage="Microsoft.WindowsAzure.Storage.StorageUri.op_Inequality (uri1, uri2)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri1" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="uri2" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
      </Parameters>
      <Docs>
        <param name="uri1">比較する最初の <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> オブジェクト。</param>
        <param name="uri2">比較する 2 番目の <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> オブジェクト。</param>
        <summary>
            比較する 2 つ<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />不一致のオブジェクト。
            </summary>
        <returns>
          <c>true</c>場合、<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />オブジェクトが等価でない値を持つ、それ以外の<c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryUri">
      <MemberSignature Language="C#" Value="public Uri PrimaryUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri PrimaryUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.StorageUri.PrimaryUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryUri As Uri" />
      <MemberSignature Language="F#" Value="member this.PrimaryUri : Uri" Usage="Microsoft.WindowsAzure.Storage.StorageUri.PrimaryUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウントのプライマリの場所のエンドポイントです。
            </summary>
        <value><see cref="T:System.Uri" />プライマリ エンドポイント。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryUri">
      <MemberSignature Language="C#" Value="public Uri SecondaryUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri SecondaryUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.StorageUri.SecondaryUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryUri As Uri" />
      <MemberSignature Language="F#" Value="member this.SecondaryUri : Uri" Usage="Microsoft.WindowsAzure.Storage.StorageUri.SecondaryUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウントの 2 次拠点のエンドポイント。
            </summary>
        <value><see cref="T:System.Uri" />拠点のエンドポイントにします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="storageUri.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            このインスタンスを表す <see cref="T:System.String" /> を返します。
            </summary>
        <returns>
            このインスタンスを表す <see cref="T:System.String" />。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>