<Type Name="Epoch" FullName="System.Fabric.Epoch">
  <TypeSignature Language="C#" Value="public struct Epoch : IComparable&lt;System.Fabric.Epoch&gt;, IEquatable&lt;System.Fabric.Epoch&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public sequential ansi serializable sealed beforefieldinit Epoch extends System.ValueType implements class System.IComparable`1&lt;valuetype System.Fabric.Epoch&gt;, class System.IEquatable`1&lt;valuetype System.Fabric.Epoch&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Epoch" />
  <TypeSignature Language="VB.NET" Value="Public Structure Epoch&#xA;Implements IComparable(Of Epoch), IEquatable(Of Epoch)" />
  <TypeSignature Language="F#" Value="type Epoch = struct" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ValueType</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IComparable&lt;System.Fabric.Epoch&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IEquatable&lt;System.Fabric.Epoch&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para> Service Fabric でパーティションの現在のバージョンを表します。 </para>
    </summary>
    <remarks>
      <para>エポックは、全体として、パーティションの構成番号です。 レプリカの構成は、プライマリ レプリカの変更、新しいプライマリ レプリカからレプリケートされた操作は、古いプライマリ レプリカによって送信されたものから新しいエポックと呼ばれますと例については、変更を設定するとします。 プライマリが変更されたというは、通常、元のプライマリ レプリカの影響を受ける失敗によって影響を受けませんセカンダリ レプリカに直接表示されません。 プライマリ レプリカが変更されたことを追跡するために、セカンダリ レプリカに伝達するがします。 使用してこのような通信が発生した、<see cref="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" />メソッドです。 ほとんどのサービスは、エポックが変更されたことを認識し、システム内の操作とイベントの相対順序を判別するエポックを比較する通常で十分ですので、エポックの内部フィールドの詳細を無視してかまいません。 比較操作は、この目的で提供されます。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Epoch (long dataLossNumber, long configurationNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 dataLossNumber, int64 configurationNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.#ctor(System.Int64,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (dataLossNumber As Long, configurationNumber As Long)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Epoch : int64 * int64 -&gt; System.Fabric.Epoch" Usage="new System.Fabric.Epoch (dataLossNumber, configurationNumber)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dataLossNumber" Type="System.Int64" />
        <Parameter Name="configurationNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="dataLossNumber">
          <para><see cref="T:System.Int64" />データの損失が疑われるたびに更新される増加する値を表すです。</para>
        </param>
        <param name="configurationNumber">
          <para><see cref="T:System.Int64" />このレプリカの設定が変更されるたびに更新が増加する値を表すです。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.Epoch" />構成番号と指定したデータ損失の数を持つクラス。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompareTo">
      <MemberSignature Language="C#" Value="public int CompareTo (System.Fabric.Epoch other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 CompareTo(valuetype System.Fabric.Epoch other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.CompareTo(System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompareTo (other As Epoch) As Integer" />
      <MemberSignature Language="F#" Value="abstract member CompareTo : System.Fabric.Epoch -&gt; int&#xA;override this.CompareTo : System.Fabric.Epoch -&gt; int" Usage="epoch.CompareTo other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IComparable`1.CompareTo(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="other">
          <para><see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</para>
        </param>
        <summary>
          <para>これと比較<see cref="T:System.Fabric.Epoch" />を指定したオブジェクト<paramref name="other" /><see cref="T:System.Fabric.Epoch" />オブジェクト。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Int32" /> を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationNumber">
      <MemberSignature Language="C#" Value="public long ConfigurationNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ConfigurationNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Epoch.ConfigurationNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property ConfigurationNumber As Long" />
      <MemberSignature Language="F#" Value="member this.ConfigurationNumber : int64 with get, set" Usage="System.Fabric.Epoch.ConfigurationNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>この現在の構成番号のプロパティを設定を取得または<see cref="T:System.Fabric.Epoch" />です。</para>
        </summary>
        <value>
          <para>返します、<see cref="T:System.Int64" />構成番号を表します。</para>
        </value>
        <remarks>
          <para>構成番号は、このレプリカの設定が変更されるたびに更新される増加する値です。 サービスが通知され、現在の構成番号の場合にのみ<see cref="M:System.Fabric.IReplicator.UpdateEpochAsync(System.Fabric.Epoch,System.Threading.CancellationToken)" />メソッドは、レプリカ セットのプライマリ レプリカを変更しようとすると、結果として呼び出されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLossNumber">
      <MemberSignature Language="C#" Value="public long DataLossNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DataLossNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Epoch.DataLossNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property DataLossNumber As Long" />
      <MemberSignature Language="F#" Value="member this.DataLossNumber : int64 with get, set" Usage="System.Fabric.Epoch.DataLossNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>この現在のデータ ロス数を取得<see cref="T:System.Fabric.Epoch" />です。</para>
        </summary>
        <value>
          <para>返します、<see cref="T:System.Int64" />現在のデータが失われる番号を表します。</para>
        </value>
        <remarks>
          <para>データ損失の数のプロパティは、レプリカのレプリカのクォーラムの損失を設定しているプライマリ レプリカを含む場合として、データの損失が疑われるたびに更新される増加する値です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (System.Fabric.Epoch other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(valuetype System.Fabric.Epoch other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.Equals(System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : System.Fabric.Epoch -&gt; bool" Usage="epoch.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="other">
          <para>現在の <see cref="T:System.Fabric.Epoch" /> オブジェクトと比較するオブジェクト。</para>
        </param>
        <summary>
          <para>決定するかどうか、指定した<see cref="T:System.Fabric.Epoch" />オブジェクトが現在<see cref="T:System.Fabric.Epoch" />オブジェクト。</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>true</languageKeyword>場合、指定した<see cref="T:System.Fabric.Epoch" />オブジェクトが現在<see cref="T:System.Fabric.Epoch" />オブジェクト。 それ以外の場合、 <languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="epoch.Equals obj" />
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
          <para>現在のオブジェクトと比較するオブジェクト。</para>
        </param>
        <summary>
          <para>指定したオブジェクトが、現在のオブジェクトと等しいかどうかを判断します。</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>true</languageKeyword>指定したオブジェクトが現在のオブジェクトと等しい、それ以外の場合<languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="epoch.GetHashCode " />
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
          <para>ハッシュ関数として機能、<see cref="T:System.Fabric.Epoch" />型です。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Int32" />現在のハッシュ コードを表す<see cref="T:System.Fabric.Epoch" />.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_Equality(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left = right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para>左側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</para>
        </param>
        <param name="right">
          <para>右側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</para>
        </param>
        <summary>
          <para>指定した 2 つの <see cref="T:System.Fabric.Epoch" /> オブジェクトの値が同一かどうかを判断します。</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>true</languageKeyword>場合の値<paramref name="left" />はの値と同じ<paramref name="right" />、それ以外の<languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_GreaterThan">
      <MemberSignature Language="C#" Value="public static bool operator &gt; (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_GreaterThan(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_GreaterThan(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &gt; (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &gt; ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left &gt; right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para>左側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</para>
        </param>
        <param name="right">
          <para>右側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</para>
        </param>
        <summary>
          <para>いずれかを指定するかどうかを判断<see cref="T:System.Fabric.Epoch" />オブジェクトが指定した別のよりも大きい<see cref="T:System.Fabric.Epoch" />オブジェクト。</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>true</languageKeyword>場合の値<paramref name="left" />の値よりも大きい<paramref name="right" />、それ以外の<languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_GreaterThanOrEqual">
      <MemberSignature Language="C#" Value="public static bool operator &gt;= (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_GreaterThanOrEqual(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_GreaterThanOrEqual(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &gt;= (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &gt;= ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left &gt;= right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para>左側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</para>
        </param>
        <param name="right">
          <para>右側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</para>
        </param>
        <summary>
          <para>いずれかを指定するかどうかを判断<see cref="T:System.Fabric.Epoch" />オブジェクトが指定した別以上<see cref="T:System.Fabric.Epoch" />オブジェクト。</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>true</languageKeyword>場合の値<paramref name="left" />より大きいかの値に等しい<paramref name="right" />、それ以外の<languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_Inequality(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="System.Fabric.Epoch.op_Inequality (left, right)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para>左側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</para>
        </param>
        <param name="right">
          <para>右側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</para>
        </param>
        <summary>
          <para>指定した 2 つあるかどうかを判断<see cref="T:System.Fabric.Epoch" />オブジェクトが異なる値を設定します。</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>true</languageKeyword>場合の値<paramref name="left" />の値とは異なる<paramref name="right" />、それ以外の<languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_LessThan">
      <MemberSignature Language="C#" Value="public static bool operator &lt; (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_LessThan(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_LessThan(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &lt; (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &lt; ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left &lt; right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para>左側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</para>
        </param>
        <param name="right">
          <para>右側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</para>
        </param>
        <summary>
          <para>いずれかを指定するかどうかを判断<see cref="T:System.Fabric.Epoch" />オブジェクトが指定した別より小さい<see cref="T:System.Fabric.Epoch" />オブジェクト。</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>true</languageKeyword>場合の値<paramref name="left" />がの値より小さい<paramref name="right" />、それ以外の<languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_LessThanOrEqual">
      <MemberSignature Language="C#" Value="public static bool operator &lt;= (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_LessThanOrEqual(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_LessThanOrEqual(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &lt;= (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &lt;= ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left &lt;= right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para>左側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</para>
        </param>
        <param name="right">
          <para>右側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</para>
        </param>
        <summary>
          <para>いずれかを指定するかどうかを判断<see cref="T:System.Fabric.Epoch" />オブジェクトが指定した別小さい<see cref="T:System.Fabric.Epoch" />オブジェクト。</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>true</languageKeyword>場合の値<paramref name="left" />がの値未満<paramref name="right" />、それ以外の<languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>