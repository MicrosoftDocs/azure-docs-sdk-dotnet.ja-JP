<Type Name="NodeId" FullName="System.Fabric.NodeId">
  <TypeSignature Language="C#" Value="public class NodeId" />
  <TypeSignature Language="ILAsm" Value=".class public ansi beforefieldinit NodeId extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NodeId" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeId" />
  <TypeSignature Language="F#" Value="type NodeId = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>ノード ID をカプセル化するクラス</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeId (System.Numerics.BigInteger high, System.Numerics.BigInteger low);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Numerics.BigInteger high, valuetype System.Numerics.BigInteger low) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.#ctor(System.Numerics.BigInteger,System.Numerics.BigInteger)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (high As BigInteger, low As BigInteger)" />
      <MemberSignature Language="F#" Value="new System.Fabric.NodeId : System.Numerics.BigInteger * System.Numerics.BigInteger -&gt; System.Fabric.NodeId" Usage="new System.Fabric.NodeId (high, low)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="high" Type="System.Numerics.BigInteger" />
        <Parameter Name="low" Type="System.Numerics.BigInteger" />
      </Parameters>
      <Docs>
        <param name="high">
          <para>最上位のコンポーネント、<see cref="T:System.Fabric.NodeId" />オブジェクト。</para>
        </param>
        <param name="low">
          <para>下位のコンポーネント、<see cref="T:System.Fabric.NodeId" />オブジェクト。</para>
        </param>
        <summary>
          <para>新しい初期化<see cref="T:System.Fabric.NodeId" />オブジェクト、指定したコンポーネントを注文高値と安値。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="nodeId.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">
          <para>現在の <see cref="T:System.Fabric.NodeId" /> と比較するオブジェクト。</para>
        </param>
        <summary>
          <para>示すかどうかこの<see cref="T:System.Fabric.NodeId" />オブジェクトと指定したオブジェクトが等しい。</para>
        </summary>
        <returns>
          <para>返します、<see cref="T:System.Boolean" />値が<languageKeyword>true</languageKeyword>オブジェクトが同じ種類し、同じ値を表す場合それ以外の場合<languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="nodeId.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>この <see cref="T:System.Fabric.NodeId" /> オブジェクトのハッシュ コードを返します。</para>
        </summary>
        <returns>
          <para>32 ビット符号付き整数ハッシュ コード。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="High">
      <MemberSignature Language="C#" Value="public System.Numerics.BigInteger High { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Numerics.BigInteger High" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeId.High" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property High As BigInteger" />
      <MemberSignature Language="F#" Value="member this.High : System.Numerics.BigInteger" Usage="System.Fabric.NodeId.High" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Numerics.BigInteger</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>最上位のコンポーネント、<see cref="T:System.Fabric.NodeId" />オブジェクト。</para>
        </summary>
        <value>
          <para><see cref="T:System.Numerics.BigInteger" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Low">
      <MemberSignature Language="C#" Value="public System.Numerics.BigInteger Low { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Numerics.BigInteger Low" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeId.Low" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Low As BigInteger" />
      <MemberSignature Language="F#" Value="member this.Low : System.Numerics.BigInteger" Usage="System.Fabric.NodeId.Low" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Numerics.BigInteger</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>下位のコンポーネント、<see cref="T:System.Fabric.NodeId" />オブジェクト。</para>
        </summary>
        <value>
          <para><see cref="T:System.Numerics.BigInteger" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (System.Fabric.NodeId value1, System.Fabric.NodeId value2);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(class System.Fabric.NodeId value1, class System.Fabric.NodeId value2) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.op_Equality(System.Fabric.NodeId,System.Fabric.NodeId)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (value1 As NodeId, value2 As NodeId) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : System.Fabric.NodeId * System.Fabric.NodeId -&gt; bool" Usage="value1 = value2" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value1" Type="System.Fabric.NodeId" />
        <Parameter Name="value2" Type="System.Fabric.NodeId" />
      </Parameters>
      <Docs>
        <param name="value1">
          <para>A<see cref="T:System.Fabric.NodeId" />と比較するオブジェクト<paramref name="value2" />です。</para>
        </param>
        <param name="value2">
          <para>A<see cref="T:System.Fabric.NodeId" />と比較するオブジェクト<paramref name="value1" />です。</para>
        </param>
        <summary>
          <para>2 つの <see cref="T:System.Fabric.NodeId" /> オブジェクトの値が同一かどうかを判断します。</para>
        </summary>
        <returns>
          <para>返します、<see cref="T:System.Boolean" />値が<languageKeyword>true</languageKeyword>オブジェクトと等価です。 それ以外の場合は、場合<languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (System.Fabric.NodeId value1, System.Fabric.NodeId value2);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(class System.Fabric.NodeId value1, class System.Fabric.NodeId value2) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.op_Inequality(System.Fabric.NodeId,System.Fabric.NodeId)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (value1 As NodeId, value2 As NodeId) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : System.Fabric.NodeId * System.Fabric.NodeId -&gt; bool" Usage="System.Fabric.NodeId.op_Inequality (value1, value2)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value1" Type="System.Fabric.NodeId" />
        <Parameter Name="value2" Type="System.Fabric.NodeId" />
      </Parameters>
      <Docs>
        <param name="value1">
          <para>A<see cref="T:System.Fabric.NodeId" />と比較するオブジェクト<paramref name="value2" />です。</para>
        </param>
        <param name="value2">
          <para>A<see cref="T:System.Fabric.NodeId" />と比較するオブジェクト<paramref name="value1" />です。</para>
        </param>
        <summary>
          <para>2 つの <see cref="T:System.Fabric.NodeId" /> オブジェクトの値が異なるかどうかを判断します。</para>
        </summary>
        <returns>
          <para>返します、<see cref="T:System.Boolean" />値が<languageKeyword>true</languageKeyword>のオブジェクトが別の値です。 それ以外の場合<languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeId.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>作成し、現在のノード ID の文字列表現を返します</para>
        </summary>
        <returns>
          <para><see cref="T:System.String" /> を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryParse">
      <MemberSignature Language="C#" Value="public static bool TryParse (string from, out System.Fabric.NodeId parsedNodeId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryParse(string from, [out] class System.Fabric.NodeId&amp; parsedNodeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.TryParse(System.String,System.Fabric.NodeId@)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryParse (from As String, ByRef parsedNodeId As NodeId) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryParse : string *  -&gt; bool" Usage="System.Fabric.NodeId.TryParse (from, parsedNodeId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.String" />
        <Parameter Name="parsedNodeId" Type="System.Fabric.NodeId&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="from">
          <para>変換するノード ID を表す文字列。</para>
        </param>
        <param name="parsedNodeId">
          <para>このメソッドが戻るときに、新しい格納<see cref="T:System.Fabric.NodeId" />に ID が含まれているノードに同等のオブジェクト<paramref name="from" />変換が成功した場合、または<languageKeyword>null</languageKeyword>変換に失敗した場合。 このパラメーターは初期化せずに渡されます。</para>
        </param>
        <summary>
          <para>ノード ID との文字列形式に変換、<see cref="T:System.Fabric.NodeId" />同等のオブジェクト。 戻り値は、演算が成功したかどうかを示します。</para>
        </summary>
        <returns>
          <returns>解析が成功したかどうかを示すブール値</returns>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>